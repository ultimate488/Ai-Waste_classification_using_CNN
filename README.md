# 🧠 Waste Classification using CNN

A Convolutional Neural Network (CNN) model to classify different types of waste for better recycling and disposal. This project aims to help automate waste segregation systems.

## 🔍 Overview

This project:
- Uses a CNN to classify waste images
- Can be trained on datasets like **organic**, **recyclable**, **hazardous**, etc.
- Supports predictions on new images

## 🛠️ Tech Used

- Python
- TensorFlow / Keras
- OpenCV (for image handling)
- NumPy, Matplotlib

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/waste-classification-cnn
cd waste-classification-cnn
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Train the model:
```bash
python train.py
```

4. Predict using an image:
```bash
python predict.py --image path_to_image.jpg
```


## ✅ To-Do

- Improve accuracy with data augmentation
- Try transfer learning (e.g. MobileNet)
- Add GUI or web interface

## 📜 License

MIT


