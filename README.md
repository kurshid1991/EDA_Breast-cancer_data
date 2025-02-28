# EDA_Breast-cancer_data
This repository contains an Exploratory Data Analysis (EDA) of a dataset with benign and tumor samples. The analysis includes data cleaning, visualization, and statistical insights to understand key patterns in the dataset.

The code focuses on classifying **benign and malignant** cells based on specific attributes describing cellular characteristics. It includes **visualizations and exploratory analysis** to support the classification process.  

## **Dataset Overview**  
The dataset originates from research conducted at the **University of Wisconsin**. It contains numerical measurements obtained from **digitized fine-needle aspirate (FNA) images** of breast cell samples.  

📌 **Dataset Link:** [Breast Cancer Data](https://github.com/kurshid1991/EDA_Breast-cancer_data/blob/main/breastcancerdata.csv)  

### **Key Details:**  
- **Total Samples:** 569 biopsy records  
- **Total Features:** 32  
  - 1 **ID column** (not useful for analysis)  
  - 1 **Diagnosis column** ("M" for malignant, "B" for benign)  
  - 30 **Numerical attributes** representing cell properties  

## **Feature Description**  
Each sample has measurements capturing the **mean, standard error**, and **worst (largest) values** for different cell nucleus characteristics:  

### **Cell Attributes:**
- 🔵 **Radius** – Average distance from the center to points on the cell perimeter  
- 🟠 **Texture** – Variation in grey-scale intensity levels  
- 🟢 **Perimeter** – Length around the cell boundary  
- 🟣 **Area** – Total size occupied by the cell  
- 🔵 **Smoothness** – Degree of variation in radius lengths  
- 🟠 **Compactness** – Ratio of perimeter² to area (indicating density)  
- 🟢 **Concavity** – Severity of concave portions in the cell boundary  
- 🟣 **Concave Points** – Number of concave areas along the boundary  
- 🔵 **Symmetry** – Measure of how symmetrical the cell is  
- 🟠 **Fractal Dimension** – Complexity of the cell shape (closer to 1 = more complex)  

## **Analysis & Visualization**  
- 📊 **Exploratory Data Analysis (EDA)** to understand feature distributions  
- 📉 **Visualizations** for cell attributes and correlations  
- 🔬 **Classification models** to distinguish benign vs. malignant samples  

## Next Step:
visit this link for apllyoing machine learning to predict the cancer subtype.
**ML Modelling for cancer subtype prediction** [Click_Here](https://github.com/kurshid1991/Breastcancer_ML-modelling)
