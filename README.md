# BSIT 63101 – Data Mining and Business Intelligence
## Practical Lesson Plan

**Course Code:** BSIT 63101  
**Lecture Hours:** 45  
**Practical Hours:** 30  
**Credit Units:** 4  

---

## Overview
This practical guide is designed to give **Year 3, Semester 1** BSIT students hands-on experience in **Data Mining** and **Business Intelligence** concepts.  
Each week includes clear goals, practical exercises, and suggested tools.

**Tools & Technologies:**
- Python (Anaconda, Jupyter Notebook)
- R (optional)
- Git & GitHub
- Tableau Public / Power BI (Free)
- OLAP tools (Excel Pivot Tables, Mondrian)
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `mlxtend`, `TextBlob`, `BeautifulSoup`, `plotly`

---

## Weekly Practicals

### **Week 1 – Introduction to Data Mining & BI**
**Goal:** Familiarize with tools and the role of DM/BI in organizations.  
**Activities:**
1. Install Anaconda and set up Jupyter Notebook.
2. Clone course GitHub repository.
3. Load a sample dataset and display basic info:
   ```python
   import pandas as pd
   df = pd.read_csv('dataset.csv')
   print(df.head())
   print(df.shape)
   print(df.describe())
````


### **Week 2 – Data Preprocessing & Exploration**

**Goal:** Learn data cleaning and exploration.
**Activities:**

1. Handle missing values (`dropna`, `fillna`).
2. Encode categorical variables.
3. Normalize numerical features.
4. Visualize distributions and correlations with seaborn.

---

### **Week 3 – Classification Techniques**

**Goal:** Build and evaluate classification models.
**Activities:**

1. Train/test split on dataset.
2. Apply Logistic Regression & Decision Tree.
3. Evaluate with accuracy, precision, recall, F1-score.

---

### **Week 4 – Clustering Techniques**

**Goal:** Group data without labels.
**Activities:**

1. Apply K-Means clustering.
2. Visualize clusters.
3. Use elbow method to find optimal k.

---

### **Week 5 – Association Rule Mining**

**Goal:** Discover relationships between variables.
**Activities:**

1. Use Apriori algorithm from `mlxtend`.
2. Generate association rules.
3. Example: Market basket analysis.

---

### **Week 6 – Text Mining & Sentiment Analysis**

**Goal:** Extract insights from text.
**Activities:**

1. Load text dataset (Twitter, IMDB).
2. Clean and tokenize text.
3. Perform sentiment analysis with `TextBlob` or `VADER`.

---

### **Week 7 – Web Mining & Social Media Analytics**

**Goal:** Collect and analyze online data.
**Activities:**

1. Scrape HTML with `BeautifulSoup`.
2. Fetch data via an API (e.g., Twitter API).
3. Analyze trending topics.

---

### **Week 8 – Data Warehousing & OLAP**

**Goal:** Explore structured storage and multidimensional analysis.
**Activities:**

1. Design a star schema.
2. Create OLAP cube in Excel or open-source tool.
3. Perform roll-up and drill-down queries.

---

### **Week 9 – Data Visualization & Dashboard Design**

**Goal:** Present data clearly to decision makers.
**Activities:**

1. Build charts in Matplotlib/Plotly.
2. Create interactive dashboards in Tableau/Power BI.

---

### **Week 10 – Business Intelligence & Reporting**

**Goal:** Automate and deliver insights.
**Activities:**

1. Generate automated reports in Jupyter.
2. Export analysis to PDF/HTML.
3. Build KPI scorecards.

---

### **Week 11 – Ethical Considerations & Privacy Issues**

**Goal:** Apply ethical guidelines to projects.
**Activities:**

1. Analyze real-world data misuse cases.
2. Implement basic anonymization.

---

### **Week 12 – Capstone Project & Future Trends**

**Goal:** Integrate all skills in a final project.
**Activities:**

1. Choose a real dataset.
2. Apply full pipeline: preprocessing → modeling → visualization → BI report.
3. Present project to class.

---

## Structure for Each Practical

1. **Recap (10 min)** – Link last week’s work to current topic.
2. **Step-by-Step Demo (20 min)** – Instructor guides through example.
3. **Hands-On Activity (40 min)** – Students work on exercise.
4. **Reflection & Submission (10 min)** – Quiz or GitHub commit.

---

## Assessment Breakdown

* Quizzes & Tests: 10%
* Lab Activities: 15%
* Take-home Assignments: 10%
* Group Tasks: 15%
* Practical Exam: 25%
* Written Exam: 25%

---

