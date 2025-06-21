# 🗑️ Garbage Classification with EfficientNetV2B2
**Developed by Sai Pranesh**

---

## 📌 Project Description
This project aims to build a smart **garbage classification system** using **transfer learning** with the **EfficientNetV2B2** architecture. The goal is to automate waste segregation for improved recycling, waste management, and environmental conservation.

---

## 🎯 Objective
To develop an accurate and efficient garbage classification model using **EfficientNetV2B2** and transfer learning that can identify different types of trash from images.

---

## ⚠️ Challenge
A key challenge addressed in this project is **class imbalance**, where some waste categories have fewer training images than others.

---

## 🧠 Why Transfer Learning?
Transfer learning allows us to:
- Reuse knowledge from large datasets (like ImageNet)
- Reduce training time and computational cost
- Improve model performance with limited labeled data

---

## 🔍 Architecture: EfficientNetV2B2
A powerful mid-sized model developed by Google, ideal for real-time classification tasks.  

### Key Features:
- ✅ Fused MBConv blocks (stability & speed)
- ✅ Progressive learning for faster generalization
- ✅ Scalable and pretrained on ImageNet

---

## 🧰 Tech Stack
| Category        | Tool / Library                |
|----------------|-------------------------------|
| Language        | Python                        |
| Deep Learning   | TensorFlow, Keras             |
| Image Handling  | OpenCV, PIL                   |
| Visualization   | Matplotlib, Seaborn           |
| Deployment (optional) | Gradio                 |
| Data Handling   | NumPy, Pandas                 |
| Pretrained Model| EfficientNetV2B2              |

---

## 📊 Dataset
The dataset contains images of various garbage types:
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash

Split into:
- Training Set (80%)
- Validation Set (20%)

---

## 📈 Model Training
- Data loaded using `image_dataset_from_directory`
- Applied data augmentation (rotation, zoom, flipping)
- EfficientNetV2B2 used as frozen base
- Custom classification head added
- Used `class_weight` to address imbalance

---

## 📉 Results
- Accuracy improved significantly using transfer learning
- Visualized training/validation loss and accuracy
- Final model tested with unseen images

---

## 🚀 Future Scope
- Convert the model to `.h5` or `.tflite` for deployment
- Deploy with **Gradio** or integrate into a mobile app
- Improve dataset balance for underrepresented classes

---

## 📸 Sample Output
In progress..

---

## 📦 How to Run
```bash
pip install tensorflow opencv-python matplotlib seaborn gradio
