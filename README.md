# 🐶🐱 Dogs vs Cats - Binary Image Classification

This project implements a binary image classifier to distinguish between images of dogs and cats using a traditional machine learning approach (SVM) rather than deep learning (CNN). The focus is on extracting basic image features and training a classification model to identify whether an image contains a cat or a dog.

---

## 📁 Dataset

The dataset used is the [Dogs vs. Cats](https://www.kaggle.com/competitions/dogs-vs-cats/data) dataset from Kaggle, which contains 25,000 labeled images of dogs and cats.

- **Training images**: 12,500 cats + 12,500 dogs  
- **Test images**: Separate unlabeled test set

---

## 📌 Objective

To train a SVM model that can accurately classify images as either a dog or a cat.

---

## 📊 Model Summary

- **Model Type**: SVM 
- **Evaluation Metrics**: Accuracy, Confusion Matrix

---

## 🛠️ Installation

Make sure you have the following packages installed:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

1. Clone the repository or download the notebook.
2. git clone `https://github.com/suman2896/SCT_ML_3.git`
3. Run the notebook `dogs-vs-cats-binary-classification.ipynb` step-by-step.

---

## 💡 Key Highlights

- Built using Keras Sequential API  
- Applied data augmentation using `ImageDataGenerator`  
- Dropout added to reduce overfitting  
- Trained on binary crossentropy loss  
---


## 🔮 Future Improvements

- Use of pre-trained CNN models (Transfer Learning) like VGG16, ResNet50  
- Early stopping and learning rate decay callbacks  
- Web deployment using Streamlit or Flask  
- Hyperparameter tuning with Keras Tuner  

--- 
