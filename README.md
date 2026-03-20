# Customer Purchase Prediction using KNN

##  Project Overview
This project applies a Machine Learning model to predict whether a customer will purchase a product based on their demographic and financial information.

The model used in this project is **K-Nearest Neighbors (KNN)**, a simple and effective classification algorithm.

---

##  Dataset
The dataset contains the following features:

- **id** – Unique identifier (removed before modeling)
- **gender** – Male/Female
- **age** – Customer age
- **salary** – Estimated salary
- **buy** – Target variable (0 = No, 1 = Yes)

---

##  Steps Performed

1. Data Loading using Pandas  
2. Data Cleaning (handling missing values if any)  
3. Encoding categorical variable (`gender`)  
4. Feature Selection (removing `id`)  
5. Train-Test Split  
6. Model Training using KNN  
7. Model Evaluation using Accuracy and Confusion Matrix  

---

##  Model Used

**K-Nearest Neighbors (KNN)**  
- Works based on distance between data points  
- `n_neighbors = 3` used in this project  

---

##  Results

- **Accuracy:** 91%  
- **Confusion Matrix:**
- [[49 3]
[ 4 24]]

- The model performs well in predicting both buyers and non-buyers, with slightly better performance for non-buyers.

---

##  Insights

- Customers with certain patterns in age and salary are more likely to purchase.  
- The model can help businesses target the right customers effectively.  

---

##  Business Strategies

1. Target customers predicted as buyers to improve marketing efficiency.  
2. Offer promotions to non-buyers to increase conversions.  

---

##  Technologies Used

- Python  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  

---

##  Files in Repository

- `customer_data.csv` → Dataset  
- `knn_model.ipynb` → Jupyter Notebook with code  
- `README.md` → Project documentation  

---

##  Conclusion

This project demonstrates how a simple Machine Learning model like KNN can be used for business decision-making and customer targeting.

---
