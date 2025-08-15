# AI Video Generation with AnimateDiff and Stable Diffusion

This project uses **AnimateDiff** and **Stable Diffusion** models to generate a short video from a text prompt.  
The script is designed to run in an environment with a GPU, such as **Google Colab**.

---

## ✨ Features

- **Text-to-Video**: Generates a 16-frame video clip from a user-provided text prompt.  
- **Open-Source Models**:  
  - `runwayml/stable-diffusion-v1-5` for image generation  
  - `guoyww/animatediff-motion-adapter-v1-5-2` for animation  
- **Optimized Performance**: Memory-efficient features such as VAE slicing and CPU offloading to run on consumer-grade GPUs.

---

## 📋 Prerequisites

- Python **3.8+**
- System with **NVIDIA GPU** and **CUDA** installed

---

## ⚙️ Setup and Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
