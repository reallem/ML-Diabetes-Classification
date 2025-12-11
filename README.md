# **Diabetes Classification using Machine Learning**

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Course](https://img.shields.io/badge/Course-Machine%20Learning-blue)
![Tools](https://img.shields.io/badge/Tools-Python%20%7C%20Jupyter%20%7C%20Scikit--Learn-lightgrey)

---

## **Overview**
This repository contains a machine learning project for the Machine Learning course.  
The goal is to classify diabetes cases using multiple machine learning models and compare their performance.

The project includes:
- Data preprocessing  
- Exploratory data analysis (EDA)  
- Model training (KNN, Decision Tree, SVM)  
- Performance evaluation and comparison  

---

## **Dataset**
The dataset used in this project is publicly available on Mendeley Data:

🔗 https://data.mendeley.com/datasets/wj9rwkp9c2/1

It contains clinical and demographic attributes related to diabetes prediction.  
The dataset is included in the `data/` directory for reproducibility.

---

## **Models Implemented**
The following supervised learning models were trained and evaluated:

### **1) K-Nearest Neighbors (KNN)**
- Implemented using scikit-learn  
- Tested with different values of k  

### **2) Decision Tree (DT)**
- Built using entropy-based splitting  
- Visual evaluation of model behavior  

### **3) Support Vector Machine (SVM)**
- Implemented using scikit-learn's SVC  
- Evaluated after preprocessing and feature scaling  

Each model’s results and analysis are included inside its corresponding notebook.

---

## **Repository Structure**
```text
ML-Diabetes-Classification/
│
├── notebooks/
│   ├── diabetes_analysis.ipynb
│   ├── dt-machinelearning-prject.ipynb
│   └── KNN.ipynb
│
├── data/
│   └── diabetes.csv
│
├── README.md
└── requirements.txt
```

---

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/ML-Diabetes-Classification.git
   cd ML-Diabetes-Classification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open and run the notebooks inside the `notebooks/` folder.

---

## **Skills Demonstrated**
- Data preprocessing  
- Exploratory data analysis (EDA)  
- Machine learning classification  
- Working with KNN, Decision Tree, and SVM  
- Model evaluation and comparison  
- Use of Jupyter Notebooks for ML workflows  

---

## **License**
This project is for academic and educational purposes.
