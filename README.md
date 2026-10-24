<h1 align="center">🧠 Advanced Pattern Recognition — CSE713 (MSc @ BRAC University)</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/EfficientNetB3-Transfer%20Learning-412991?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ConvNeXt-Deep%20Learning-F7931E?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/BRAC%20University-MSc%20CSE-012d35?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Grade-A-success?style=for-the-badge"/>
</p>

<p align="center">
  MSc group project — <strong>Human Action Recognition (HAR)</strong> using deep learning.
  Comparing EfficientNetB3 and ConvNeXtTiny with full preprocessing, augmentation,
  and evaluation pipeline.
</p>

---

## 📚 Course Info

- **Course:** CSE713 — Advanced Syntactic Pattern Recognition
- **Program:** MSc in Computer Science & Engineering
- **University:** BRAC University
- **Grade:** A (90–96) → CGPA 4.00

---

## 🎯 Task: Human Action Recognition (HAR)

Classify human actions from image sequences using state-of-the-art CNN architectures with transfer learning.

---

## 🔬 Models

| Model | Architecture | Strength |
|---|---|---|
| **EfficientNetB3** | Compound-scaled CNN | Balanced accuracy/efficiency |
| **ConvNeXtTiny** | Modernised ResNet | Strong feature extraction |

---

## 🏗️ Pipeline

```
HAR Dataset (action image sequences)
      │
      ▼
Data Preprocessing
(resize, normalise, label encoding)
      │
      ▼
Data Augmentation
(flip, rotate, crop, colour jitter)
      │
      ▼
Transfer Learning
(ImageNet pretrained → fine-tune on HAR)
      │
      ▼
Training with early stopping + LR scheduling
      │
      ▼
Evaluation
(Accuracy, Precision, Recall, F1, Confusion Matrix)
      │
      ▼
EfficientNetB3 vs ConvNeXtTiny comparison
```

---

## 📊 Evaluation Metrics

- Classification accuracy per action class
- Macro/weighted Precision, Recall, F1
- Confusion matrix analysis
- Training/validation loss curves

---

## 🚀 Getting Started

```bash
git clone https://github.com/Ramisa-16/CSE713.git
cd CSE713
pip install -r requirements.txt
jupyter notebook
```

---

## 🛠️ Tech Stack

**Python** · **TensorFlow/Keras** · **EfficientNetB3** · **ConvNeXtTiny** · **NumPy** · **Matplotlib** · **scikit-learn**

---

## 👩‍💻 Author

**Ramisa Sharar Nidhi** — MSc CSE @ BRAC University (CGPA 4.00/4.00)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ramisashararnidhi-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/ramisashararnidhi)
[![GitHub](https://img.shields.io/badge/GitHub-Ramisa--16-181717?style=flat&logo=github)](https://github.com/Ramisa-16)
