# 🧠 Skin Disease Prediction Web App

This project is a web application for **skin disease detection** using Machine Learning. It allows users to upload an image of a skin lesion and predicts the category of the disease using a hybrid model based on **VGG16** and **SVM**.

## 🚀 Objective

The main goal of this project is to assist in the **early and accurate diagnosis** of skin diseases by providing a fast, easy-to-use tool that classifies skin lesions into one of seven categories:

- Basal cell carcinoma  
- Squamous cell carcinoma  
- Melanoma  
- Nevus (mole)  
- Actinic keratosis  
- Benign skin lesions (excluding nevus)  
- Dermatofibroma  

## 🧩 Methodology

1. **Data Preprocessing**:
   - Handling missing data and removing unusable images (e.g., with white borders)
   - Label encoding
   - Dataset balancing for fair training

2. **Feature Extraction**:
   - Using a pre-trained **VGG16** network without its classification layers
   - Generating feature vectors for each image

3. **Classification**:
   - Training a **Support Vector Machine (SVM)** with a linear kernel using the extracted features

4. **Web Deployment**:
   - Built with **Flask**
   - User-friendly interface for uploading an image and receiving real-time prediction
   - Trained model saved in a `.pkl` file for seamless integration

## 🧪 Results

The model achieved a test accuracy of **77.8%**, which is considered good for image-based dermatological classification.


## 🛠️ Technologies Used

- Python  
- Flask  
- Scikit-learn  
- TensorFlow / Keras (VGG16)  
- NumPy, Pandas  
- HTML/CSS  

## 👥 Authors
 
- 👤 MOUMENE Fatima Zahra  

Developed as part of the **Master’s in Data Science and Intelligent Systems** program.


## 📸 How It Works

1. 📥 User uploads a skin image  
2. 🧠 Features are extracted using VGG16  
3. 🤖 SVM model classifies the image  
4. ✅ Result is displayed instantly (e.g., "Melanoma", "Nevus", etc.)

---

> ⚠️ **Disclaimer**: This project is intended for educational purposes only and should not be used for real medical diagnosis.



