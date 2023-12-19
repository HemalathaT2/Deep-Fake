# Deep-Fake

## Overview

This project is aimed at creating deepfake videos using advanced AI techniques. It includes features such as face swapping and face enhancement, providing a powerful tool for video editing and creative content creation.

## Features

- Face swapping: Replace faces in a target video with faces from a source image.
- Face enhancement: Improve the quality and appearance of faces in a video.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-deepfake-project.git
   cd your-deepfake-project

- Install dependencies:
  pip install -r requirements.txt

- Additional steps for GPU support (if applicable):
  # Install GPU dependencies (replace cuda_version with your CUDA version)
  pip install torch==your_torch_version+cpu torchvision==your_torchvision_version+cpu torchaudio==your_torchaudio_version+cpu -f         
  https://download.pytorch.org/whl/cu111/torch_stable.html

- Run the project:
  python run.py --target path/to/target_video.mp4 --source path/to/source_image.jpg -o path/to/output_video.mp4 --execution-provider cpu --frame-processor face_swapper face_enhancer

- Usage
  Replace path/to/target_video.mp4 with the path to your target video.
  Replace path/to/source_image.jpg with the path to your source image.
  Replace path/to/output_video.mp4 with the desired output path.
  Adjust other parameters as needed.
  
- Configuration
  Modify run.py to customize execution providers, frame processors, and other settings.
  Refer to the documentation for advanced configuration options.
