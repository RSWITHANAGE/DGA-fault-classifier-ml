# Transformer Fault Classification Using Machine Learning

## 📌 Project Overview
Power transformers are critical assets in power generation and transmission systems. Reliable operation ensures uninterrupted electricity supply. This project focuses on **identifying mixtures of transformer faults** using **Dissolved Gas Analysis (DGA) data** collected from the **Yugadanavi Power Plant**.  

Traditional DGA diagnostic methods often fail to detect multiple simultaneous fault types. To address this, we implemented a **machine learning–based classification framework** capable of detecting both single and mixed faults, supporting predictive and condition-based maintenance.

---

## 🎯 Objectives
- Detect **single and mixed transformer faults** accurately
- Enable **faster and reliable fault diagnosis**
- Support predictive maintenance to **reduce downtime and operational costs**
- Evaluate multiple machine learning models for robustness and accuracy

---

## 📊 Methodology

1. **Data Preprocessing**
   - Cleaning and normalization of DGA measurements
   - Handling missing and anomalous data

2. **Exploratory Data Analysis**
   - Distribution of gas concentrations
   - Identification of fault patterns and correlations

3. **Feature Engineering**
   - Extraction of meaningful features from raw DGA data
   - Dimensionality reduction for improved model efficiency

4. **Class Balancing**
   - Applied **SMOTE** to address imbalanced fault classes

5. **Model Development**
   - Evaluated multiple algorithms:
     - Logistic Regression  
     - Support Vector Machines (SVM)  
     - Random Forests  
     - Neural Networks  
     - Ensemble Methods

---

## 📈 Performance and Results
- **Random Forest and ensemble models** outperformed traditional DGA approaches.
- Achieved **higher accuracy and robustness** in detecting complex fault mixtures.
- Demonstrated capability to support **predictive maintenance and condition monitoring**.

---

## 🌍 Applications
- Predictive maintenance in power plants
- Reducing unplanned transformer outages
- Optimizing maintenance schedules and costs
- Improving overall reliability of power transmission systems
