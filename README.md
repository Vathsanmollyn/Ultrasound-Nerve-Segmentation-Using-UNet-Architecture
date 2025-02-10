# Ultrasound Nerve Segmentation using U-Net

## Overview
This project focuses on segmenting ultrasound images of nerves using a U-Net model. The model is trained to detect nerve structures in medical ultrasound images to assist in automated diagnostics.

## Features
- Implementation of U-Net for medical image segmentation
- Preprocessing and augmentation of ultrasound images
- Evaluation and performance metrics visualization

## Installation & Setup
To set up the environment, install the required dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib opencv-python scikit-learn
```

## Dataset
- The dataset consists of ultrasound images with labeled nerve segmentation masks.


## File Structure
```
Ultrasound-Nerve-Segmentation/
│── notebooks/            # Jupyter notebooks for model training & testing
│── data/                 # Dataset files (not uploaded if too large)
│── README.md             # Project documentation
```

## Model Details
The project employs a U-Net architecture for efficient segmentation of ultrasound images.
- Model Architecture: U-Net (Fully Convolutional Network)
- Training: Supervised learning on labeled segmentation masks
- Evaluation Metrics: Dice Coefficient, IoU (Intersection over Union)


## Future Work
- Improve segmentation accuracy with larger datasets and advanced architectures.
- Deploy as a real-time application for medical professionals.

## License
This project is licensed under the MIT License.

## Contact
For any questions, open an issue or reach out via email.

