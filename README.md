#  Leukemia Cell Classification using Deep Learning

A comparative deep learning study for automatic leukemia cell classification using microscopic blood cell images from the C-NMC dataset.

This project evaluates the performance of several state-of-the-art deep learning architectures for distinguishing between:

-  ALL (Acute Lymphoblastic Leukemia)
-  HEM (Healthy Cells)

---

##  Models Implemented

- Custom CNN
- MobileNetV2
- EfficientNet-B0
- Vision Transformer (ViT)

---

##  Dataset

**C-NMC Leukemia Classification Dataset**

The dataset contains microscopic images of blood cells and is organized into two classes:

| Class | Description |
|--------|------------|
| ALL | Leukemia Cells |
| HEM | Healthy Cells |

---

## Data Preprocessing

- Image resizing (224 × 224)
- Normalization
- Train / Validation / Test split
- Balanced sampling between classes

---

##  Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

---

##  Results

| Model | Accuracy |
|---------|----------|
| Custom CNN | 84% |
| MobileNetV2 | 82% |
| EfficientNet-B0 | 86% |
| Vision Transformer (ViT) | **90%** |

The Vision Transformer achieved the best overall performance among all evaluated models.

---

##  Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

##  Project Structure

```
leukemia-classification-deep-learning/
│
├── README.md
├── requirements.txt
├── notebooks/
├── images/
├── results/
└── models/
```

---

##  Future Work

- Hybrid CNN-Transformer architectures
- Explainable AI (Grad-CAM)
- Clinical robustness evaluation
- Multi-class leukemia classification


##  Author

**Nasim Abdirahman Ismail**

Master's Student in Artificial Intelligence

Muğla Sıtkı Koçman University

Turkey 🇹🇷
