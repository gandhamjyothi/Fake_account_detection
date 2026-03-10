# Fake Account Detection Using Data Science and Machine Learning

## 📌 Project Overview

Fake accounts on social media platforms can spread spam, misinformation, and malicious content. Detecting these accounts manually is difficult due to the large number of users.

This project implements a **machine learning-based system** to automatically detect fake accounts using profile features such as account age, number of posts, and number of friends.

The system uses an **Artificial Neural Network (ANN)** model to classify accounts as **Fake** or **Genuine**.

---

## 🎯 Objectives

* Detect fake social media accounts using machine learning.
* Analyze profile attributes and user behavior.
* Improve security and trust in online social networks.
* Build a prediction system that classifies accounts automatically.

---

## 🧠 Technologies Used

* Python
* Data Science Libraries

  * Pandas
  * NumPy
  * Matplotlib
* Machine Learning

  * Artificial Neural Network (ANN)
  * Scikit-learn
  * Keras
* GUI

  * Tkinter

---

## 📂 Project Files

This repository contains the following files:

* **Main.py** – Main application with GUI and ANN model.
* **dataset.txt** – Training dataset containing social media account profiles.
* **test.txt** – Dataset used for testing the prediction model.

---

## 📊 Dataset Description

The dataset contains various features of social media accounts used for classification. 

| Feature      | Description                          |
| ------------ | ------------------------------------ |
| Account_Age  | Age of the social media account      |
| Gender       | User gender indicator                |
| User_Age     | Age of the user                      |
| Link_Desc    | Presence of profile description      |
| Status_Count | Number of posts or statuses          |
| Friend_Count | Number of friends/followers          |
| Location     | Location availability                |
| Location_IP  | IP based location information        |
| Status       | Target label (0 = Genuine, 1 = Fake) |

---

## ⚙️ Methodology

The system follows these steps:

1. Upload dataset
2. Preprocess dataset
3. Train ANN model
4. Evaluate model accuracy
5. Predict whether an account is **Fake or Genuine**

The dataset is split into:

* **80% training data**
* **20% testing data**

---

## 🤖 Machine Learning Model

The project uses an **Artificial Neural Network (ANN)** with the following architecture: 

* Input Layer: 8 features
* Hidden Layer 1: 200 neurons (ReLU activation)
* Hidden Layer 2: 200 neurons (ReLU activation)
* Output Layer: 2 neurons (Softmax)

The model is trained using:

* **Adam Optimizer**
* **Categorical Crossentropy Loss**
* **200 training epochs**

---

## 📈 Output

The system displays:

* Number of accounts in dataset
* Training and testing samples
* Model accuracy
* Accuracy vs Loss graph
* Prediction results for test profiles

---

## 🖥️ Application Interface

The system includes a **GUI interface** that allows users to:

* Upload dataset
* Preprocess data
* Train ANN model
* View accuracy graph
* Predict fake accounts

---

## ▶️ How to Run the Project

### Step 1

Install required libraries

pip install pandas numpy matplotlib scikit-learn keras tensorflow

### Step 2

Run the program

python Main.py

### Step 3

Use the GUI to:

1. Upload dataset
2. Preprocess dataset
3. Run ANN algorithm
4. View accuracy graph
5. Predict fake or genuine profiles

---

## 💡 Applications

* Social media security
* Fake profile detection
* Spam account detection
* Online fraud prevention

---

## 🔮 Future Enhancements

* Use deep learning models for improved accuracy
* Integrate real-time social media APIs
* Deploy the model as a web application
* Use larger datasets for better prediction performance

---
