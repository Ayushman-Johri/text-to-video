AI Video Generation with AnimateDiff and Stable Diffusion
This project uses the AnimateDiff and Stable Diffusion models to generate a short video from a text prompt. The script is designed to run in an environment with a GPU, such as Google Colab.

Features
Text-to-Video: Generates a 16-frame video clip based on a user-provided text prompt.

Open-Source Models: Utilizes the runwayml/stable-diffusion-v1-5 model for image generation and the guoyww/animatediff-motion-adapter-v1-5-2 motion adapter for animation.

Optimized: Includes memory-efficient optimizations (VAE slicing and CPU offloading) to run on consumer-grade GPUs.

Prerequisites
Python 3.8+

A system with an NVIDIA GPU and CUDA installed.

Setup and Installation
Clone the repository:

Bash

git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
Install the required libraries:

Bash

pip install diffusers transformers accelerate torch
How to Run
Open the copy_of_text_to_video.py script.

Modify the prompt variable to describe the video you want to create:

Python

prompt = "a majestic lion walking in slow motion across the savanna, cinematic lighting"
Run the script from your terminal:

Bash

python copy_of_text_to_video.py
The script will download the necessary models, generate the video, and save it as generated_video.mp4 in the same directory. It will also display the video if run in a Jupyter or Colab environment.

Example Output
Here is an example video generated with the prompt "a majestic lion walking in slow motion...":
(You can add a screenshot or GIF of your generated video here)
