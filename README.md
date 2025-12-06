# 🧠 Intel Image Classification using CNN

## 📋 Project Overview
This project focuses on building a **Convolutional Neural Network (CNN)** to classify natural scene images from the **Intel Image Classification Dataset** into six categories:
- Buildings 🏢
- Forest 🌲
- Glacier 🧊
- Mountain 🏔️
- Sea 🌊
- Street 🛣️

The model was trained using **TensorFlow** and **Keras**, and achieves strong accuracy through careful preprocessing, normalization, and optimization techniques.

---
### **Dataset**

**Link On Kaggle** : https://www.kaggle.com/datasets/puneet6060/intel-image-classification

#### **📌 Dataset Size**

| Attribute             | Description                                               |
| --------------------- | --------------------------------------------------------- |
| **Dataset Name**      | **Intel Image Classification**                            |
| **Total Images**      | **25,000** (approx.)                                      |
| **Training Images**   | **14,034**                                                |
| **Testing Images**    | **3,000**                                                 |
| **Validation Images** | **7301**                                                  |
| **Number of Classes** | **6** (Buildings, Forest, Glacier, Mountain, Sea, Street) |
| **Data Format**       | **JPEG Images**                                           |

---

## ⚙️ Features
- Data loading and preprocessing using **OpenCV** and **NumPy**
- CNN model built with multiple convolutional, pooling, and dense layers
- **Dropout** and **EarlyStopping** to reduce overfitting
- Evaluation on test data with accuracy and loss visualization
- Predictions on unseen images (seg_pred folder)
- Performance visualization using **Matplotlib** and **Seaborn**

---

---

## 🧠 Training Details
- **Epochs:** 50 (with EarlyStopping)
- **Batch Size:** 64
- **Optimizer:** Adam
- **Loss Function:** Categorical Crossentropy
- **Evaluation Metric:** Accuracy

---

---

## 🧮 Technologies Used
| Category | Tools / Libraries |
|-----------|-------------------|
| Language | Python 🐍 |
| Deep Learning | TensorFlow, Keras |
| Data Processing | NumPy, OpenCV |
| Visualization | Matplotlib, Seaborn |
| Dataset | Intel Image Classification (Kaggle) |

---





---

## 📁 Dataset Structure
```
intel-image-classification/
│
├── seg_train/       # Training data (6 folders - one per class)
├── seg_test/        # Test data (6 folders)
└── seg_pred/        # Prediction data (unlabeled images)
```
---

## 📈 Future Improvements
- Implement **Transfer Learning** with VGG16 or ResNet50
- Add **Batch Normalization** for faster convergence
- Experiment with **data augmentation** and **learning rate schedulers**

---

## 👨‍💻 Author
**Muhammed Waheed Muhammed**  
📍 Giza, Egypt  
📧 [wahedmohamed688@gmail.com](mailto:wahedmohamed688@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/muhammed-waheed-4856a7245) | [GitHub](https://github.com/MuhammedWaheed)

--
