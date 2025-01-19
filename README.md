# Image Inpainting Quality Analyzer

This tool evaluates the quality of inpainted images by comparing them to the original images using common image quality metrics: **PSNR**, **SSIM**, **MSE**, and **MAE**. It also provides visual feedback by comparing the difference between the original and inpainted images.

## Features

- **PSNR, SSIM, MSE, MAE**: Standard image quality metrics to evaluate inpainting performance.
- **Region-based Analysis**: Offers more detailed analysis of specific regions through mask-based evaluation.
- **Visualization**: Displays the original, inpainted, and mask images with the difference and histograms for better insight.

## Usage

1. **Run the Application**: Start the Colab interface by executing the script.
2. **Upload Images**: Upload the **original**, **inpainted**, and **mask** images.
3. **View Results**: Check the calculated metrics (PSNR, SSIM, MSE, MAE) and visual results.

For using an interactive tool developed based on this repo, you can visit the Hugging Face page at:  
[Hugging Face Image Inpainting Metrics](https://huggingface.co/spaces/Greygt/Image-Inpainting-Metrics)
