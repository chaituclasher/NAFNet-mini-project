# **Nonlinear Activation-Free U-Net Architecture for Image Restoration - Mini Project**

This repository contains the code, resources, and documentation for a deep learning-based image restoration project using the **Nonlinear Activation-Free Network (NAFNet)**. The primary objective of this project is to restore motion-blurred images by leveraging NAFNet’s efficient, activation-free design, achieving high performance with reduced computational costs.

## **Project Overview**
This project implements the NAFNet architecture to restore images impacted by motion blur. With a streamlined **U-Net backbone**, linear layers, and no nonlinear activations, **NAFNet** enables high-quality image restoration with lower computational overhead. Benchmarking against other state-of-the-art models demonstrates NAFNet's advantages in terms of speed, efficiency, and image fidelity.

## **Features**
- **Image Restoration:** Restores blurred images and enhances image quality using NAFNet.
- **Performance Benchmarking:** Compares PSNR and SSIM values with other state-of-the-art models, including **MIMO-Unet**, **DeepRFT**, and **Restormer**.
- **Real-Time Processing Compatibility:** Optimized for fast inference, making it suitable for applications requiring immediate feedback.

## **Installation**
1. Clone the repository:
    ```bash
    git clone https://github.com/chaituclasher/NAFNet-Image-Restoration.git
    cd NAFNet-Image-Restoration
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## **Usage**
To run the image restoration pipeline:
```bash
python main.py --input_dir ./data/blurred_images --output_dir ./results/deblurred_images
