### Week 2 – Data Preprocessing & Exploration
**Goal:** Learn to clean, transform, and explore datasets.

---

#### **1. Free PowerPoint Slides**
- **“Data Preprocessing in Data Mining”** – Covers handling missing values, outlier detection, normalization, and encoding.  
  

- **“Exploratory Data Analysis (EDA) in Python”** – Practical examples with pandas, matplotlib, seaborn.  
  

- **“Data Cleaning and Preprocessing”** – Brief slides on data quality, transformation, and integration.  
 
---

#### **2. Dataset Suggestions (Free & Open)**
- **Titanic Dataset** (Kaggle, CSV format) – Ideal for missing value handling, encoding categorical features.  
  [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)  

- **Iris Dataset** (UCI Machine Learning Repository) – Good for normalization & basic EDA.  
  [https://archive.ics.uci.edu/ml/datasets/iris](https://archive.ics.uci.edu/ml/datasets/iris)  

- **Adult Income Dataset** (UCI) – Best for encoding categorical variables and scaling.  
  [https://archive.ics.uci.edu/ml/datasets/adult](https://archive.ics.uci.edu/ml/datasets/adult)

---

#### **3. Practical Activities**
1. **Loading Data**
   ```python
   import pandas as pd
   df = pd.read_csv('titanic.csv')
   df.head()
````

2. **Handling Missing Values**

   ```python
   # Drop missing rows
   df.dropna(inplace=True)

   # Or fill missing
   df['Age'].fillna(df['Age'].mean(), inplace=True)
   ```

3. **Encoding Categorical Variables**

   ```python
   df = pd.get_dummies(df, columns=['Sex', 'Embarked'])
   ```

4. **Normalizing Data**

   ```python
   from sklearn.preprocessing import MinMaxScaler
   scaler = MinMaxScaler()
   df[['Age', 'Fare']] = scaler.fit_transform(df[['Age', 'Fare']])
   ```

5. **Basic EDA**

   ```python
   import seaborn as sns
   sns.heatmap(df.corr(), annot=True, cmap='coolwarm')
   ```

---

#### **4. Submission**

* Push `.ipynb` notebook with:

  * Data cleaning steps
  * Encoded and normalized dataset
  * At least 3 visualizations
* Include a short summary of findings.

---

Do you want me to make **offline-ready dataset links** for Week 2?
```
