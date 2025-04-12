# Dengue Severity Prediction using Machine Learning and Clustering

Dengue is a viral disease that primarily affects tropical and subtropical regions and is especially prevalent in South-East Asia. This mosquito-borne disease sometimes triggers nationwide epidemics, resulting in a large number of fatalities. The development of Dengue Haemorrhagic Fever (DHF) accounts for most severe cases, especially among children under the age of ten, often progressing to a critical state known as Dengue Shock Syndrome (DSS).

In this study, we analyzed two separate datasets from two different countries – Vietnam and Bangladesh, referred to as VDengu and BDengue, respectively.

---

## Vietnam Dataset (VDengu)

- As the dataset was structured, supervised learning models were effective for predictive analysis.
- Among them, the Decision Tree Classifier and XGBoost models produced the best outcomes.
- Furthermore, Shapley Additive Explanation (SHAP) was applied over the XGBoost model to assess the significance of individual attributes.
- SHAP dependence plots were used to identify the range for each attribute against the number of DHF or DSS cases.

---

## Bangladesh Dataset (BDengue)

- As the dataset was unstructured, an unsupervised learning technique — hierarchical clustering — was applied.
- Clustering was based on vital blood components extracted from complete blood count reports.
- These clusters were further analyzed to identify the attributes that led to DHF or DSS conditions.

---

## Technologies Used

- Python (Google Colab)
- XGBoost
- Decision Tree Classifier
- Hierarchical Clustering
- SHAP (Shapley Additive Explanations)
- Scikit-learn
- Pandas, Numpy, Matplotlib, Seaborn

---

## Acknowledgements

- The datasets were collected from clinical studies conducted in Vietnam and Bangladesh.


---
