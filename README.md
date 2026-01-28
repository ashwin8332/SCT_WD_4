# ✋ SCT_WD_4 – Hand Gesture Recognition System

## 📌 Project Overview

This project focuses on building a **Hand Gesture Recognition System** capable of accurately identifying and classifying different hand gestures from image or video data. The system enables **intuitive human–computer interaction (HCI)** and can be integrated into **gesture-based control systems**, touchless interfaces, and assistive technologies.

The implementation uses a **machine learning / deep learning pipeline** trained on the **Leap Gesture Recognition Dataset** and follows industry-standard practices for data preprocessing, model training, evaluation, and reproducibility.

---

## 🎯 Objectives

* Accurately classify multiple hand gestures from visual data
* Build a scalable and reusable ML pipeline
* Enable gesture-based control for real-world applications
* Maintain a clean, professional, and reproducible project structure

---

## 🧠 Use Cases

* Gesture-controlled user interfaces
* Touchless systems (kiosks, AR/VR)
* Assistive technology for accessibility
* Smart devices and IoT control
* Human–robot interaction

---

## 📂 Dataset Information

### Dataset Name

**Leap Gesture Recognition Dataset**

### Dataset Source

Kaggle Dataset: *gti-upm/leapgestrecog*

🔗 Dataset Link:
[https://www.kaggle.com/datasets/gti-upm/leapgestrecog](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

### Dataset Description

The dataset contains grayscale hand gesture images captured using a Leap Motion Controller. It includes multiple gesture classes recorded from different users, making it suitable for robust gesture classification tasks.

**Key Characteristics:**

* Image-based gesture samples
* Multiple gesture classes
* Multiple users for better generalization
* Structured folder hierarchy by gesture and subject

### Gesture Classes

Examples include:

* Palm
* Fist
* Thumbs Up
* Thumbs Down
* Index
* OK Sign
* C Shape
* L Shape

---

## ⬇️ How to Download the Dataset

### Method 1: Kaggle Website

1. Visit the dataset link on Kaggle
2. Log in to your Kaggle account
3. Click **Download**
4. Extract the ZIP file into the project directory

### Method 2: Kaggle API (Recommended)

```bash
pip install kaggle
```

1. Generate a Kaggle API token from your Kaggle account settings
2. Place `kaggle.json` in:

   ```
   ~/.kaggle/
   ```
3. Download the dataset:

   ```bash
   kaggle datasets download -d gti-upm/leapgestrecog
   ```
4. Extract the dataset:

   ```bash
   unzip leapgestrecog.zip
   ```

---

## ⚙️ Tech Stack

### Programming Language

* Python 3.x

### Libraries & Frameworks

* NumPy
* Pandas
* OpenCV
* TensorFlow / Keras or PyTorch
* Scikit-learn
* Matplotlib / Seaborn

---

## 🔄 Workflow

1. **Data Collection** – Download dataset from Kaggle
2. **Preprocessing** – Resizing, normalization, label encoding
3. **Data Splitting** – Train / validation / test split
4. **Model Architecture** – CNN-based deep learning model
5. **Training** – Optimized using backpropagation
6. **Evaluation** – Accuracy, precision, recall, confusion matrix
7. **Prediction** – Real-time or batch gesture classification

---

## 🧪 Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/ashwin8332/SCT_WD_4.git
cd SCT_WD_4
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook
```

4. Run `hand_gesture_detection.ipynb`

---

## 📈 Results

The trained model demonstrates strong classification performance across multiple gesture classes, achieving high accuracy and stable convergence. The results validate the effectiveness of CNN-based approaches for vision-based gesture recognition.

---

## 🔮 Future Enhancements

* Real-time webcam-based gesture recognition
* Video stream support
* Transformer-based vision models
* Mobile and edge-device deployment
* Integration with smart devices and applications

---

## 👤 Author

**Ashwin Vincent Koonissery**
GitHub: [https://github.com/ashwin8332](https://github.com/ashwin8332)

---

## 📜 License

This project is intended for **educational and research purposes**. Please follow the dataset’s original license terms when using it for commercial applications.

---

⭐ If you find this project useful, feel free to star the repository!
