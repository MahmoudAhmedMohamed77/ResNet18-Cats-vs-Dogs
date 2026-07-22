# 🐱 ResNet18 Cats vs Dogs Classification

A deep learning project that classifies cat and dog images using **ResNet18 Transfer Learning** with **PyTorch**.

---

## 📌 Features

- Pretrained ResNet18
- Transfer Learning
- Data Augmentation
- Training & Validation
- Save Best Model
- Single Image Prediction
- Accuracy & Loss Visualization

---

## 🛠 Tech Stack

- Python
- PyTorch
- TorchVision
- Matplotlib
- Pillow

---

## 📂 Project Structure

```
ResNet18-Cats-vs-Dogs/
│
├── dataset/
├── models/
├── results/
├── main.py
├── predict.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📁 Dataset Structure

```
dataset/
│
├── training_set/
│   ├── cats/
│   └── dogs/
│
├── test_set/
│   ├── cats/
│   └── dogs/
│
└── single_prediction/
```

---

## 🚀 Installation

```bash
git clone https://github.com/YOUR_USERNAME/ResNet18-Cats-vs-Dogs.git

cd ResNet18-Cats-vs-Dogs

pip install -r requirements.txt
```

---

## ▶️ Train the Model

```bash
python main.py
```

---

## 🔍 Predict a Single Image

```bash
python predict.py
```

---

## 🧠 Model Information

| Item | Value |
|------|-------|
| Model | ResNet18 |
| Framework | PyTorch |
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Image Size | 224 × 224 |

---

## 📊 Results

After training, the project saves:

- Best trained model
- Loss Curve
- Accuracy Curve

---

## 📜 License

This project is released under the MIT License.

---

## 👨‍💻 Author

Mahmoud Eid
## Dataset

The dataset used in this project is the Cats vs Dogs dataset from Kaggle.

Download it from: https://www.kaggle.com/datasets/dhirensk/cats-vs-dogs-training8000test2000
