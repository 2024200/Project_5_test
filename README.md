### Description

This project was an integrated end of term assignment for my data analytics, data preparation and machine learning. It involved analysing a healthcare dataset to improve treatment outcomes and operational efficiency. The tasks included descriptive and inferential statistical tests, feature engineering, and dimensionality reduction using LDA and PCA. Both supervised and unsupervised models were used 

### Dataset

The full dataset is linked here [LINK](https://github.com/2024200/Project_5_test/blob/2e3f62a90d7de844c6a935d2a9a6e4d9c2d08b3b/Dataset/Data%20Dictionary%20Healthcare%20copy%202.docx)

5000 entries, total 15 columns - Memory Usage: 586.1+ KB

### Notebook

Models used 

- Logistic Regression
- Nearest Neighbours
- Support Vectors
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- Naive Bayes
- Quadratic DA
- Neural Net

Final model 

QDA

|  | Notebook |
| --- | --- |
| Collab | https://colab.research.google.com/drive/19EallcvY0wrMVP4LQWGjHL7Yfy3Ocgjo?usp=sharing |
| Kaggle | https://www.kaggle.com/code/jldoyle/p5-patient-classification-and-clustering/notebook |
| Github | https://github.com/2024200/Project_5_test/blob/2e3f62a90d7de844c6a935d2a9a6e4d9c2d08b3b/P5_Patient_Classification_and_Clustering.ipynb |

### Tech-stack + Libraries

- **Python version**: 3.10.12
- **Packages**: **Packages:** datetime, sys, warnings, numpy, pandas, matplotlib, seaborn, plotly, shap, scipy, statsmodels, sklearn, tensorflow, scikeras, yellowbrick

### **Results**

* **The dataset used was randomly generated with target feature having four variables, which contributed to the poor results observed in the statistical tests and models.***

Stats 

- ANOVA and Shapiro tests indicated non-normal distribution, leading to the use of the Kruskal-Wallis test, which found no significant differences in metrics across categories.
- T-tests on blood pressure also showed non-normal distribution, prompting the use of the Mann-Whitney U test, which found no significant differences in blood pressure.
- Chi-Squared tests on categorical features revealed no significant associations with the disease.

<img width="478" alt="Screenshot 2024-08-18 at 11 29 03" src="https://github.com/user-attachments/assets/2d88d995-1f5f-4f40-8a63-c0269c41f126">
