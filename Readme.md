# ADC-Net: A Deep Attention-Based Framework for Preserving Fine Image Details in Denoising

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository provides the implementation of **ADCNET**, an attention-based deep learning model for image denoising. The main code is contained in the notebook `Denoising_code.ipynb`, designed for denoising grayscale and RGB images corrupted by synthetic or real noise.

## 🔗 GitHub Repository

**URL**: [https://github.com/Aaru5246/ADCNET.git](https://github.com/Aaru5246/ADCNET.git)

**DOI**: [https://doi.org/10.5281/zenodo.15857292](https://doi.org/10.5281/zenodo.15857292)


## 🚀 Features

- Attention Convolution Blocks (ACBs) for enhanced feature representation.
- Efficient architecture suitable for real-time or near-real-time denoising.
- Supports bit-plane and color-component-level processing.
- Clean and modular code for training, testing, and inference.


## 🧪 How to Use

1. Clone the repository:

\`\`\`bash
git clone https://github.com/Aaru5246/ADCNET.git
cd ADCNET
\`\`\`

2. Launch the notebook:

\`\`\`bash
jupyter notebook Denoising_code.ipynb
\`\`\`

3. Inside the notebook:
   - Load your **noisy** and **ground-truth** images.
   - Train the ADCNET model or load a pre-trained checkpoint.
   - Evaluate and visualize denoised output.

---

## 📊 Results

Sample denoised images and performance metrics (e.g., PSNR, SSIM) are included in the notebook after training/testing runs.

---

## 📎 Citation

If you use this work in your research, please cite:

\`\`\`bibtex
@software{jain2025adcnet,
  author       = {Arti Jain and Co-authors},
  title        = {ADCNET: Attention-based Deep Convolutional Network for Image Denoising},
  year         = 2025,
  publisher    = {GitHub},
  journal      = {GitHub Repository},
  url          = {https://github.com/Aaru5246/ADCNET}
}
\`\`\`

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---



## 🌟 Acknowledgements

This project was developed as part of ongoing research in robust image denoising techniques using attention-based deep learning architectures.
