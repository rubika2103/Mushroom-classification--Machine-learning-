# 🍄 Mushroom Classification Using Machine Learning

This project uses **Machine Learning** to classify mushrooms as **edible or poisonous** based on their physical attributes.  
The dataset contains 8,000+ mushroom samples with 22 categorical features.

The goal is to build a classification model that accurately predicts whether a mushroom is safe to eat.

---

## Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Data Preprocessing
Since the mushroom dataset is fully **categorical**, the preprocessing includes:

- Label Encoding / One-Hot Encoding  
- Handling missing values  
- Feature scaling (optional)  
- Train-test split  
- Converting all attributes into numeric form  

---

## 🧠 Machine Learning Models Used
The following models were trained and compared:

- Decision Tree Classifier  
- Random Forest Classifier  
- Logistic Regression  
- Naive Bayes  
- Support Vector Classifier (SVC)  

Best performing model: **Random Forest** (commonly highest accuracy)

---

##  Model Evaluation
Evaluation metrics include:

- Accuracy Score  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- Classification Report  

Example Output:  
- **Accuracy:** ~100% (dataset is very clean and separable)  
- Random Forest gives strongest performance  

---

## Visualizations
- Correlation heatmap (after encoding)  
- Feature importance plot  
- Confusion matrix  
- Barplots for class distribution  
- Comparison of model accuracy  

---

## Key Insights
- Cap color, odor, gill size, and gill color are the most important factors.  
- Mushrooms with “foul”, “pungent”, or “fishy” odor are almost always poisonous.  
- Dataset is perfectly classifiable due to distinct feature patterns.  

---

## Conclusion
This project demonstrates:

✔ Data preprocessing for categorical variables  
✔ Building multiple ML classification models  
✔ Performance evaluation  
✔ Feature importance analysis  
✔ Real-world prediction workflow  

The model can reliably classify mushrooms as edible or poisonous based on their attributes.

---



