# MNIST Handwritten Digit Recognition using CNN

This project implements a **Convolutional Neural Network (CNN)** using **TensorFlow and Keras** to classify handwritten digits (0–9) from the **MNIST dataset**. The model is trained, evaluated, and used to visualize predictions on test images.

---

## 📌 Project Overview

* Dataset: MNIST Handwritten Digits
* Task: Image classification (digits 0–9)
* Model Type: Convolutional Neural Network (CNN)
* Frameworks: TensorFlow, Keras
* Visualization: Matplotlib

The model achieves high accuracy by learning spatial features using convolution and pooling layers.

---

## 🧠 Model Architecture

The CNN architecture consists of:

1. Input Layer (28×28 grayscale images)
2. Convolution Layer (32 filters, 3×3) + ReLU
3. Max Pooling Layer (2×2)
4. Convolution Layer (64 filters, 3×3) + ReLU
5. Max Pooling Layer (2×2)
6. Convolution Layer (64 filters, 3×3) + ReLU
7. Flatten Layer
8. Dense Layer (64 units, ReLU)
9. Output Layer (10 units, Softmax)

Loss Function: `sparse_categorical_crossentropy`
Optimizer: `Adam`
Metrics: `Accuracy`

---

## ⚙️ Installation & Setup

### 1. Create a Virtual Environment (Recommended)

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 2. Install Required Dependencies

```bash
pip install tensorflow keras numpy matplotlib
```

---

## ▶️ How to Run

Execute the script from **Command Prompt or PowerShell**:

```bash
python main.py
```

> **Note:** Running from terminal is recommended to properly display Matplotlib plots.

---

## 📊 Output & Results

* Training accuracy reaches ~98–99% within 5 epochs
* Final test accuracy is printed in the console
* A test image is displayed along with:

  * True label
  * Model prediction

Example output:

```
Test accuracy: 98.40%
```

---

## 🖼 Visualization

The project includes a utility function to display test images with predictions:

* Grayscale image visualization
* True vs predicted label shown in the plot title



## 📁 Project Structure

```
har_recognition/
│── main.py
│── README.md
│── .venv/
```

---


## 👤 Author

**Abdullah Ali**
Flutter & ML Enthusiast

---

## 📜 License

This project is for educational purposes and is free to use and modify.
