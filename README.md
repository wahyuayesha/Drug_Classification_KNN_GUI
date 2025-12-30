# 💊 drug classification with knn and gui

[![GitHub stars](https://img.shields.io/github/stars/wahyuayesha/Drug_Classification_KNN_GUI?style=for-the-badge)](https://github.com/wahyuayesha/Drug_Classification_KNN_GUI/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/wahyuayesha/Drug_Classification_KNN_GUI?style=for-the-badge)](https://github.com/wahyuayesha/Drug_Classification_KNN_GUI/network/members)
[![GitHub issues](https://img.shields.io/github/issues/wahyuayesha/Drug_Classification_KNN_GUI?style=for-the-badge)](https://github.com/wahyuayesha/Drug_Classification_KNN_GUI/issues)


this project is a **machine learning mini project** that aims to predict the **type of drug required by a patient** using the **k-nearest neighbors (knn)** algorithm.  
the project is also equipped with a **tkinter based gui** that allows users to input patient data and receive predictions interactively.

this project was created as a **learning medium** to understand the complete workflow of knn, from data processing to deployment in a simple application.

---

## 📌 main features

- drug type prediction based on patient data  
- knn algorithm implemented from scratch (without pre-built model libraries)  
- data preparation and data analysis  
- model training and evaluation  
- interactive gui using tkinter for user input and prediction  
- suitable for beginners learning machine learning and knn  

---

## 📊 input parameters

the model predicts the drug type based on the following patient features:

- **age** → patient age  
- **sex** → gender  
- **blood pressure** → blood pressure level (low / normal / high)  
- **cholesterol** → cholesterol level (normal / high)  
- **na to k** → sodium-to-potassium ratio  

the output of the model is the **predicted drug class**.

---

## 🧠 algorithm used

### k-nearest neighbors (knn)

- calculates distances between data points  
- determines the k closest neighbors  
- applies majority voting to decide the drug class  

the knn algorithm is implemented **from scratch** to help fully understand its internal logic.

---

## 🔧 development stages

this project follows several main stages:

### 1. data preparation
- data cleaning  
- categorical data encoding  
- numerical feature normalization  

### 2. data analysis
- dataset exploration  
- understanding relationships between features  
- data distribution analysis  

### 3. model development
- knn implementation from scratch  
- distance calculation function  
- class voting mechanism  

### 4. training and evaluation
- train-test data splitting  
- model performance testing  
- accuracy evaluation  

### 5. gui with tkinter
- patient data input form  
- prediction button  
- real-time prediction result display  

---

## 🖥️ gui overview

the gui is built using **tkinter** and is designed to:

- accept patient input data  
- run the knn model  
- display the predicted drug type  

the interface is kept simple to make it easy for beginners to understand and modify.

---

## 📚 learning objectives

this project is intended to:

- understand the basic concept of knn  
- learn the end-to-end machine learning workflow  
- practice integrating a machine learning model into a gui application  
- strengthen algorithmic thinking by implementing models from scratch  

---

## 🚀 technologies used

- python  
- pandas  
- numpy  
- tkinter  

---

## 📝 note

this project is **not intended for real medical use** and is created solely for **educational purposes**.

![artificial intelligence](https://img.shields.io/badge/artificial_intelligence-0052cc?style=for-the-badge)
![machine learning](https://img.shields.io/badge/machine_learning-102230?style=for-the-badge)
![knn](https://img.shields.io/badge/knn_from_scratch-ff9800?style=for-the-badge)
![gui](https://img.shields.io/badge/gui_tkinter-4caf50?style=for-the-badge)
![learning project](https://img.shields.io/badge/learning_project-9c27b0?style=for-the-badge)
