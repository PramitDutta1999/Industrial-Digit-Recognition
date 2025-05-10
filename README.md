# Industrial Digit Recognition
**Lightweight MobileNetV2 with Geometric Transformations and GAN-Based Upsampling**

## Overview

This project was developed as part of the **ENGG*6100 Machine Vision** course at the University of Guelph. It focuses on serial number recognition in industrial parts using a lightweight MobileNetV2 deep learning architecture. To improve recognition accuracy and handle class imbalance, both geometric transformations and GAN-based data augmentation were explored.

## Key Features

- Lightweight **MobileNetV2** architecture adapted for digit classification  
- **Geometric transformation-based upsampling** for minority class balance  
- **GAN-generated synthetic data** to enhance diversity  
- Class-wise evaluation using precision, recall, and F1-score  
- Grad-CAM visualizations for model interpretability

## Dataset

- 1,885 industrial part images labeled with serial numbers  
- High class imbalance with 12 distinct serial number categories  
- Images include variations in font, size, blurring, and labeling errors
- **The dataset is not permitted to be shared publicly. Please contact the course instructor to request access.**

## Notes

- **Change all file paths** in the scripts as per your local environment.
- For experimental design, methodology, and performance metrics, please refer to the accompanying report.
- GAN-based augmentation was limited to two classes due to resource constraints.
- The model was trained and evaluated on Google Colab using TensorFlow and OpenCV.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
This project was completed as part of the UNIV*6100: Machine Vision course at the University of Guelph under the guidance of Professor Medhat Moussa. Thanks to the AI Enabled Medical Imaging Analysis Lab for their support and resources throughout this work.
