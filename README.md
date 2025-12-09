#  Breast Cancer Prediction using K-Means & KNN

This project performs **Breast Cancer Tumor Classification** using:
- **K-Means Clustering** (Unsupervised)
- **K-Nearest Neighbors (KNN)** (Supervised Classification)

The dataset used is the **Breast Cancer Wisconsin Dataset** (`Dataset.csv`).

---

##  Features of the Project
- Data loading & preprocessing  
- Label encoding (M → 1, B → 0)  
- Feature scaling using MinMaxScaler  
- Train–test split (80/20)  
- K-Means clustering  
- KNN classification  
- Accuracy, Precision, Recall, F1-score  
- Confusion matrix & classification report  

---

##  Algorithms Used

### 1️⃣ K-Means Clustering
- Unsupervised  
- Groups data into **2 clusters**  
- Compares cluster output vs actual labels  

### 2️⃣ K-Nearest Neighbors (KNN)
- Supervised  
- k = 5  
- Predicts Malignant / Benign  

---

##  Requirements

Install required libraries:

```bash
pip install pandas numpy scikit-learn
