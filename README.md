# Handwritten Digit Recognizer 🔢

A deep learning project that classifies handwritten digits (0–9) using an Artificial Neural Network (ANN) trained on the MNIST dataset.

## 📌 Project Overview

- **Dataset:** MNIST (70,000 grayscale images of handwritten digits)
- **Model:** Fully Connected ANN (Dense layers)
- **Framework:** TensorFlow / Keras
- **Task:** Multi-class classification (10 classes)

## 🧠 Model Architecture

| Layer | Type | Units | Activation |
|-------|------|-------|------------|
| Input | Flatten | 784 | — |
| Hidden 1 | Dense + Dropout | 128 | ReLU |
| Hidden 2 | Dense + Dropout | 64 | ReLU |
| Output | Dense | 10 | Softmax |

## 📊 Results

- ✅ Test Accuracy: ~98%
- Includes training/validation accuracy & loss plots
- Confusion matrix on test set

## 🚀 How to Run

1. Clone the repo:
```bash
   git clone https://github.com/your-username/digit-recognizer.git
   cd digit-recognizer
```
2. Install dependencies:
```bash
   pip install -r requirements.txt
```
3. Open the notebook:
```bash
   jupyter notebook Digit_aiml.ipynb
```

## 📦 Requirements

See `requirements.txt`

## 📁 Project Structure

```
digit-recognizer/
│
├── Digit_aiml.ipynb          # Main notebook
├── digit_recognizer_model.keras  # Saved model (optional)
├── requirements.txt
└── README.md
```
