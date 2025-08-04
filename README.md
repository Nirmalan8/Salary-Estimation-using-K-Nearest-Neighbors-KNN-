#  Salary Estimation using K-Nearest Neighbors (KNN)

This project uses the K-Nearest Neighbors (KNN) classification algorithm to predict whether an individual's annual salary is **greater than $50K** or **less than or equal to $50K**. The model is trained on demographic and employment-related features from a dataset.

---

##  Problem Statement

Can we predict a person's salary category (`<=50K` or `>50K`) based on features like education level, age, occupation, etc. 
This binary classification task helps us understand how different factors impact income level.

---

## Dataset

The dataset used is a CSV file named `salary.csv`, which contains:
- Personal information (age, education, etc.)
- Employment details (occupation, workclass, hours-per-week, etc.)
- Target variable: `income` (<=50K or >50K)


---

## 🧠 Machine Learning Algorithm

**K-Nearest Neighbors (KNN)**  
KNN is a simple, distance-based classification algorithm. It classifies new instances by checking the majority class of its K nearest neighbors in the training set.

---

## 🧪 Steps Performed

1. Import necessary Python libraries
2. Load and explore the dataset
3. Convert the target column to numeric
4. Split data into training and testing sets
5. Apply feature scaling (important for KNN)
6. Tune K value to find the best one
7. Train final KNN model with best K
8. Evaluate model using confusion matrix and accuracy score

---

##  K Value Optimization

We tested different values of **K from 1 to 49**, calculated the error rate for each, and plotted it to find the optimal `K` value.

<img width="1266" height="675" alt="Screenshot 2025-08-04 090648" src="https://github.com/user-attachments/assets/a0bcfd29-1629-402b-aab4-7783b1526cc4" />

---

##  Final Result

-  **Best K Value:** 14  
-  **Accuracy Achieved:** _add your accuracy here (e.g., 82.79%)_  
-  **Evaluation Metrics:** Confusion Matrix, Accuracy

---

##  Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

