# Image Generator using ComfyUI & Stable Diffusion

## 📌 Overview
This project utilizes **ComfyUI** and **Stable Diffusion** to generate AI-powered images based on text prompts.  
It provides a powerful yet simple way to generate high-quality images directly from the console.

## 🛠️ Setup & Installation
Follow these steps to set up the project on your local machine:

1. **Download & Install ComfyUI**
   - Download ComfyUI from the official [GitHub repository](https://github.com/comfyanonymous/ComfyUI).
   - Extract the files and navigate to the `ComfyUI` folder.

2. **Download Stable Diffusion Model**
   - Get a Stable Diffusion `.safetensors` model from [Hugging Face](https://huggingface.co/stabilityai) or another source.
   - Place it inside the `ComfyUI/models/checkpoints/` directory.

3. **Run ComfyUI**
   - Navigate to the ComfyUI directory.
   - Run the following command to start the server:
     ```
     python main.py
     ```
   - Once running, access the UI at:
     ```
     http://127.0.0.1:8188
     ```

## 🚀 Generating Images
1. Open the ComfyUI interface.
2. Enter your desired prompt in the text box.
3. Click the **Generate** button to create an image.
4. The generated images will be saved in the output directory.

## 🖼️ Sample Outputs
Here are some AI-generated images using this setup:

![Sample Image 1](samples/sample1.png)
![Sample Image 2](samples/sample2.png)

## 📌 Features
- Text-to-Image generation using Stable Diffusion.
- Easy setup with ComfyUI.
- Customizable model support.
- Works locally without an internet connection.

---
### 🔗 Useful Links
- [ComfyUI GitHub](https://github.com/comfyanonymous/ComfyUI)
- [Stable Diffusion Models](https://huggingface.co/Comfy-Org/stable-diffusion-v1-5-archive/blob/main/v1-5-pruned-emaonly-fp16.safetensors)
