# 🌿 Plant Disease Detection using EfficientNetB0

A deep learning-based plant disease classification system developed using **TensorFlow** and **EfficientNetB0** with **transfer learning** and **fine-tuning**. The model is trained on the **PlantVillage** dataset to classify plant leaf diseases across multiple crop species.

---

## 📌 Project Overview

Plant diseases can significantly reduce crop yield and quality. Early detection helps farmers take timely action to prevent disease spread.

This project uses a pretrained **EfficientNetB0** model to automatically classify plant leaf diseases from images with high accuracy.

---

## 🚀 Features

- Plant disease classification using deep learning
- Transfer learning with EfficientNetB0
- Fine-tuning for improved performance
- Data augmentation
- Validation accuracy close to **97%**
- Single image prediction
- Classification report
- Confusion matrix
- Saved trained model for future deployment

---

## 📂 Dataset

**Dataset:** PlantVillage

- 54,000+ leaf images
- 38 plant disease classes
- Healthy and diseased plant leaves
- Multiple crop species including:
  - Apple
  - Corn
  - Grape
  - Orange
  - Peach
  - Pepper
  - Potato
  - Raspberry
  - Soybean
  - Squash
  - Strawberry
  - Tomato

---

## 🧠 Model Architecture

- EfficientNetB0 (ImageNet pretrained)
- Transfer Learning
- Fine-Tuning
- Global Average Pooling
- Dropout
- Dense Softmax Output Layer

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Pillow

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Validation Accuracy | **96.96%** |
| Validation Loss | **0.0898** |

---

## 📁 Project Structure

```
Plant-Disease-Detection/
│
├── notebook/
│   └── Plant_Disease_Detection.ipynb
│
├── model/
│   └── plant_disease_efficientnetb0.keras
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Plant-Disease-Detection.git
```

Move into the project directory:

```bash
cd Plant-Disease-Detection
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Notebook

Open the notebook using Jupyter Notebook or upload it to Kaggle.

Run all cells to:

- Load the dataset
- Train the model
- Fine-tune the model
- Evaluate performance
- Save the trained model
- Predict plant diseases on sample images

---

## 📈 Evaluation

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Classification Report
- Confusion Matrix

---

## 🔮 Future Improvements

- Streamlit web application
- Mobile application integration
- Real-time camera prediction
- Grad-CAM visualization
- Disease treatment recommendations

---

## 👨‍💻 Author

**Wisal Khan**

BS Computer Science

Machine Learning | Deep Learning | Computer Vision

GitHub: https://github.com/wisalkhan-icp

LinkedIn: [https://linkedin.com/in/YOUR_LINKEDIN](https://www.linkedin.com/in/wisal-khan-53a09b351/)

---

## ⭐ Acknowledgements

- TensorFlow
- Keras
- PlantVillage Dataset
- EfficientNet Research
