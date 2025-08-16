# CIFAR-10-CNN-Classifier


This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

---

## 📌 Project Overview
- Trains a CNN on the CIFAR-10 dataset (60,000 32x32 color images in 10 classes).
- Achieves classification of objects like airplanes, cars, birds, cats, etc.
- Provides functionality to save and load trained models.
- Includes inference script to test predictions on new images.

---

## 🚀 Features
- CNN model with multiple convolution and fully connected layers
- Training and validation loop with accuracy tracking
- Saving and loading trained models (`model.pth`)
- Prediction script to test new images
- Requirements file (`requirements.txt`) for easy setup

---

## 📂 Dataset (CIFAR-10)
The CIFAR-10 dataset has the following labels:

| Label Index | Class Name |
|-------------|------------|
| 0           | Airplane   |
| 1           | Automobile |
| 2           | Bird       |
| 3           | Cat        |
| 4           | Deer       |
| 5           | Dog        |
| 6           | Frog       |
| 7           | Horse      |
| 8           | Ship       |
| 9           | Truck      |

---

## 🛠️ Installation

Clone the repository:
```bash
git clone https://github.com/your-username/cnn-cifar10.git
cd cnn-cifar10
```

Install dependencies:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

---


## 📋 Requirements
Main dependencies are listed in \`requirements.txt\`:
- torch
- torchvision
- matplotlib
- numpy
- Pillow

Install them with:
\`\`\`bash
pip install -r requirements.txt
\`\`\`

---

## 📊 Results
Example prediction output:
\`\`\`
Predicted Label: Truck
\`\`\`

---

## 🤝 Contributing
Feel free to fork this repo and submit pull requests!

---

## 📜 License
This project is licensed under the MIT License.
EOL
