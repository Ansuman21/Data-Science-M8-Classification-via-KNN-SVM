# **Battle of Classification Models: KNN vs SVM for Superior Predictions**

## **Project Overview**
This project evaluates the performance of two widely used machine learning algorithms, **K-Nearest Neighbors (KNN)** and **Support Vector Machines (SVM)**, on a classification task. By utilizing different feature subsets and a robust evaluation methodology, the project identifies the optimal model for accurate and reliable predictions.


## **Business Case**
Accurate classification models are critical in industries like healthcare, finance, and marketing to make data-driven decisions. Misclassification can lead to significant losses, such as incorrect diagnosis in healthcare or targeting the wrong customer segments in marketing campaigns. 

This project aims to:
- Identify the most suitable algorithm (KNN or SVM) for classification.
- Recommend feature selection strategies to enhance model performance.
- Provide actionable insights based on model evaluation.

---

## **Methodology**
The project follows a structured approach:

### **1. Model Selection**
- Two machine learning algorithms were chosen:
  - **K-Nearest Neighbors (KNN):** A simple and intuitive distance-based algorithm.
  - **Support Vector Machines (SVM):** A robust algorithm that uses hyperplanes to separate data points.

### **2. Feature Selection**
- Models were evaluated with different subsets of features to optimize performance:
  - **KNN Model 1:** All features.
  - **KNN Model 2:** Selected features optimized for KNN.
  - **SVM Model 1:** Features tailored for SVM.
  - **SVM Model 2:** Alternative feature set for SVM.

### **3. Cross-Validation**
- **5-Fold Cross-Validation** was employed to assess the models’ generalizability, using **accuracy** as the evaluation metric.

### **4. Model Evaluation**
Each model was evaluated on the **test dataset** using the following metrics:
- **Accuracy:** Percentage of correct predictions.
- **Precision:** Accuracy of positive predictions.
- **Recall:** Proportion of true positives identified.
- **F1 Score:** Balance between precision and recall.

### **5. Comparison and Analysis**
- Performance metrics from cross-validation and test dataset evaluations were consolidated into a table for direct comparison.
- Recommendations were made based on the analysis.

---

## **Key Results**
- **Cross-Validation:**
  - KNN Model 1 had the lowest cross-validation score.
  - SVM Model 1 achieved the highest generalizability.
  
- **Test Set Evaluation:**
  - **SVM Model 1** emerged as the best model across all metrics, achieving the highest **accuracy**, **precision**, **recall**, and **F1 Score**.
  - KNN Model 2 outperformed KNN Model 1, demonstrating the importance of effective feature selection.

---

## **Recommendations**
1. **Adopt SVM Model 1** for classification tasks due to its consistent and superior performance.
2. Incorporate feature selection as a critical step in the modeling pipeline to improve results.
3. Leverage the insights gained to further refine and adapt models for similar classification problems.

---

## **Conclusion**
This project highlights the importance of a systematic evaluation process in selecting the best-performing model. The use of robust metrics and feature selection techniques ensures reliable and actionable results, making **SVM Model 1** the optimal choice for accurate predictions.

---

## **Author**
**Ansuman Patnaik**  
**MS in Data Science & Analytics, Yeshiva University**  
**Email:** ansu1p89k@gmail.com  
