# Night Vision Image Enhancement
This project demonstrates classical image processing techniques to enhance dark images and simulate a night vision effect using Python and OpenCV.

## 📌 Features

- Gamma Correction for brightness adjustment
- CLAHE for local contrast enhancement
- Gaussian Blur and Sharpening
- Edge Detection using combined Canny and Laplacian
- Green Channel Enhancement for night vision aesthetics
- PSNR and Edge Pixel Ratio analysis

## 📁 Files Included

- `D121221095_Final_Project_Viskom.ipynb`: Main Jupyter Notebook for image enhancement
- Sample images:
  - `gangsta.JPEG`: Original bright image
  - `itam.JPEG`: Simulated dark image
- Output images:
  - Processed night vision image
- `README.md`: This file

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/drive/11yWIsaIgTMDCqqZ-l2Oyr_txImP_ugBX?usp=sharing).
2. Upload `gangsta.JPEG` and `itam.JPEG`.
3. Execute each cell sequentially to view the transformation process.
4. Final outputs and analysis will be displayed inline.

## 🔧 Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- scikit-image (`skimage.metrics` for PSNR)

## 📊 Evaluation

- **PSNR**: Measures image quality against the original. In this project, PSNR was ~5.18 dB due to spectrum shift to green but structural fidelity was maintained.
- **Edge Pixel Ratio**: 3.41% of the image represents structural edges—indicating informative contour detection without excessive noise.

## 📌 Author

Muh. Adhim Rahman Rusdi — D121221095
"""