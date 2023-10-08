# Real-time Drowsiness and Distraction Detection System for Drivers

## Overview 🚀 👁️ 🚗

This is a real-time Drowsiness and Distraction Detection System using transfer learning. It addresses critical concerns related to driver safety and attentiveness, particularly in the context of road safety and human-machine interaction. It detects the driver's eye state and recognizes various forms of distraction behaviors by analyzing real-time visual data, allowing for timely warnings and intervention.

## Datasets 📊

**Drowsiness Detection Model:**
- MRL eye dataset
- Closed Eyes In The Wild (CEW) dataset
- ZJU eyeblink dataset

**Distraction Detection Model:**
- Statefarm driver distraction dataset

## Novelty 🌟

One of the key highlights of this project is the use of a combined dataset that has not been used in any of the existing systems. This means that the model will be trained on a more diverse dataset, which could lead to improved performance.

## Keywords

- Transfer Learning
- Driver Monitoring System
- Pre-trained Models
- OpenCV
- TensorFlow
- NumPy
- Matplotlib
- Keras
- Scikit-Learn
- Deep Learning
- Python (Programming Language)

## Getting Started

Download the specified datasets.
Download the jupyter notebook files and change the paths to the datasets, and other data in the code.
Run it

## License 📜

This project is licensed under the MIT - see the [LICENSE.md](https://github.com/Justy-11/R4D/blob/988f3ce100134d355b0251eb3e851338114116f7/LICENSE) file for details.

## Acknowledgments 🙏

## Folder structure 📁

```
R4D/
│
├── DrowsinessDetectionOnCombinedDataset/
│   ├── saved_data/    
|   |   ├── models/
|   |   |   └── model and history files
|   |   |
|   |   └──  saved .npy and .pkl image array files
|   |  
│   ├── 01_Data_Preprocessing.ipynb
|   ├── 02_Model_Training.ipynb
|   ├── 03_Model_evaluation.ipynb
│   └── 04_Realtime_detection.ipynb
│
├── haarcascade_eye.xml
│
├── haarcascade_frontalface_default.xml
|
└── README.md, LICENSE
