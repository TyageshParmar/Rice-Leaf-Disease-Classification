# 🌾 Rice Leaf Disease Classification

This project focuses on building a deep learning model to detect and classify common rice leaf diseases using image data. It helps automate early disease detection in crops like rice, reducing reliance on manual inspections and improving agricultural outcomes.

## 📌 Project Overview

- **Objective**: To identify and classify rice leaf diseases from images using CNN and transfer learning.
- **Dataset**: 120 labeled images categorized into:
  - Leaf Smut
  - Brown Spot
  - Bacterial Leaf Blight
- **Approach**: 
  - Baseline CNN model
  - Transfer Learning using MobileNetV2
  - Performance evaluation and comparison

## 📊 Dataset Details

- Format: `.jpg`
- Total Images: 120 (40 per class)
- Source: Provided as part of PRCP-1001 assignment

## 🧠 Models Used

| Model                 | Accuracy |
|----------------------|----------|
| Baseline CNN         | 74%      |
| MobileNetV2 (TL)     | 83% ✅   |

- **Transfer Learning model performed significantly better** in accuracy, recall, and precision.

## 🧪 Techniques Applied

- Data preprocessing & resizing
- Image augmentation
- CNN architecture tuning
- Transfer learning (MobileNetV2)
- Model evaluation using confusion matrix, classification report

## 🚧 Challenges Faced

- Limited dataset size
- Overfitting in baseline CNN
- Class imbalance
- Tuning MobileNetV2 for small dataset without overfitting

## ✅ Results & Recommendation

- The **MobileNetV2-based model is recommended** for deployment due to its superior accuracy and generalization.
- Transfer learning proved to be highly effective for small medical/agricultural image datasets.

## 🛠️ Tools & Libraries

- Python, TensorFlow/Keras
- NumPy, Matplotlib
- Google Colab / Jupyter Notebook

## 📁 File Structure


## ✍️ Author

**Tyagesh Parmar**  
AI & Data Science Enthusiast  
[GitHub](https://github.com/TyageshParmar) | [Portfolio](https://tyageshparmar.github.io)
---
