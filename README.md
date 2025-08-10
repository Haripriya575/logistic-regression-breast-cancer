 Logistic Regression (Binary Classification)

 Objective
The goal of this task is to implement **Logistic Regression** to classify whether a tumor is malignant or benign using the **Breast Cancer Wisconsin dataset**.  
This task is part of my AI & ML Internship.



Dataset
We used the **Breast Cancer Wisconsin dataset** directly from `scikit-learn`.



 Steps Performed
1. **Data Loading** – Loaded the dataset into a Pandas DataFrame.
2. **Data Preprocessing** – Standardized features using `StandardScaler`.
3. **Train/Test Split** – Split into 80% training and 20% testing sets.
4. **Model Building** – Implemented `LogisticRegression` from `scikit-learn`.
5. **Model Evaluation** – Used Accuracy, Precision, Recall, F1 Score, Confusion Matrix, and ROC-AUC.
6. **Visualization** – Plotted the ROC Curve and Sigmoid function.



 Results
- **Accuracy**: ~97%
- **Precision**: ~98%
- **Recall**: ~96%
- **F1 Score**: ~97%
- **ROC-AUC Score**: ~0.99



 Sample Output
Confusion Matrix:  
![Confusion Matrix](confusion_matrix.png)

ROC Curve:  
![ROC Curve](roc_curve.png)





 Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn



Status
 Completed and submitted as part of AI & ML Internship Task 4.

