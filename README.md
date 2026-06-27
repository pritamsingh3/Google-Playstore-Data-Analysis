# 📱 Google Play Store Data Analysis & Feature Engineering

## 📌 Project Overview

This project focuses on **Data Preprocessing**, **Feature Engineering**, **Feature Selection**, and **Machine Learning Preprocessing** using the **Google Play Store Dataset**.

The objective is to transform raw, inconsistent data into a clean, structured, and machine-learning-ready dataset by applying various preprocessing and feature engineering techniques.

---

## 📂 Dataset

- **Dataset:** Google Play Store Dataset
- **Records:** 10,000+ Apps
- **Domain:** Mobile Applications
- **Target Variable:** Rating

---

# 🚀 Project Workflow

### 1️⃣ Data Understanding
- Loaded dataset
- Explored dataset structure
- Checked data types
- Identified numerical and categorical features

---

### 2️⃣ Data Cleaning
- Removed duplicate records
- Handled missing values
- Fixed inconsistent data
- Converted text columns into numerical format

Columns cleaned:

- Reviews
- Installs
- Price
- Size
- Android Version

---

### 3️⃣ Missing Value Handling

Applied:

- Mean Imputation
- Mode Imputation
- Constant Value Imputation

---

### 4️⃣ Outlier Detection & Treatment

Performed:

- Boxplots
- IQR Method
- Z-Score Method
- Outlier Capping

---

### 5️⃣ Encoding

Applied:

- One-Hot Encoding
- Binary Encoding (Paid_App_Flag)

---

### 6️⃣ Feature Scaling

Applied:

- StandardScaler
- MinMaxScaler

---

### 7️⃣ Date Feature Engineering

Extracted from **Last Updated**

- Year
- Month
- Day
- Quarter
- Day Name

---

### 8️⃣ Feature Engineering

Created the following new features:

- Reviews_Per_Install
- Paid_App_Flag
- App_Age
- Minimum_Android_Version
- Category_Average_Rating

---

### 9️⃣ Feature Selection

Performed:

- Correlation Analysis
- SelectKBest
- Random Forest Feature Importance

---

### 🔟 Train-Test Split

- 80% Training Data
- 20% Testing Data

---

### 1️⃣1️⃣ Automated Preprocessing Pipeline

Implemented using:

- Pipeline
- ColumnTransformer

Pipeline includes:

- Missing Value Imputation
- One-Hot Encoding
- Standard Scaling

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 📁 Project Structure

```
Google-Playstore-Data-Analysis
│
├── Google Play Store Data Preprocessing and Feature Engineering Report.pdf
├── MAIN.ipynb
├── output.png
├── output1.png
├── output2.png
├── output3.png
└── README.md
```

---

# 📊 Key Business Insights

- Most apps on the Play Store are free.
- Reviews and installs strongly indicate app popularity.
- Recently updated apps generally maintain better ratings.
- User engagement can be estimated using Reviews_Per_Install.
- Category-wise average ratings help compare app performance across categories.
- Android version compatibility provides useful insights for device support.

---

# 🤖 Machine Learning Readiness

The dataset was prepared for Machine Learning by:

- Removing duplicates
- Handling missing values
- Converting text to numerical values
- Encoding categorical variables
- Scaling numerical features
- Creating meaningful engineered features
- Selecting important features
- Building an automated preprocessing pipeline

---

# 📈 Feature Selection Methods

- Correlation Analysis
- SelectKBest
- Random Forest Feature Importance

These methods were used to identify the most important features affecting the **Rating**.

---

# 📚 Learning Outcomes

Through this project, I learned:

- Data Cleaning
- Missing Value Treatment
- Feature Engineering
- Feature Scaling
- Outlier Detection
- Feature Selection
- Machine Learning Preprocessing
- Pipeline
- ColumnTransformer
- Train-Test Split
- Preparing real-world datasets for Machine Learning

---

# 📷 Project Outputs

The project includes visualizations such as:

- Boxplots
- Correlation Matrix
- Feature Importance
- Data Analysis Outputs

---

# ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/pritamsingh3/Google-Playstore-Data-Analysis.git
```

2. Navigate to the project folder

```bash
cd Google-Playstore-Data-Analysis
```

3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open the notebook

```bash
jupyter notebook MAIN.ipynb
```

---

# 📌 Future Improvements

- Build an App Rating Prediction Model
- Deploy the model using Streamlit or Flask
- Perform Hyperparameter Tuning
- Build an interactive dashboard using Power BI

---

# 👨‍💻 Author

**Pritam Singh**

🎓 B.Tech – Artificial Intelligence & Data Science

### Connect with Me

- GitHub: https://github.com/pritamsingh3
- LinkedIn: https://www.linkedin.com/in/pritamsingh03/

---

# ⭐ If you found this project useful, don't forget to star the repository!
