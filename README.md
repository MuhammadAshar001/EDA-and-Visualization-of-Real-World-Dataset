# EDA-and-Visualization-of-Real-World-Dataset
## Titanic Dataset EDA & Visualization 

This project presents an Exploratory Data Analysis (EDA) of the Titanic Dataset as part of Task 1 of the Data Science Internship. The main goal was to clean the data, analyze distributions, identify outliers, and visualize insights from both categorical and numerical features.

---

## 📌 Task Overview

**Objective:**  
Perform EDA and visualization on a real-world dataset (Titanic) to uncover meaningful insights and prepare it for further analysis or modeling.

---

## 📂 Dataset Used

- **Dataset**: Titanic Dataset (`Titanic-Dataset.csv`)
- **Source**: Provided with the internship task or publicly available on Kaggle.

---

## ⚙️ Steps Performed

### 1. 🔧 Data Cleaning
- Handled missing values in:
  - `Age` (imputed with median)
  - `Embarked` (imputed with mode)
  - `Cabin` (dropped due to sparsity)
- Removed duplicate rows.
- Detected and treated outliers in `Fare` using the IQR method and replaced them with the median.

---

### 2. 📊 Data Visualization

#### 📌 Categorical Variables (Bar Charts)
- `Sex`, `Pclass`, `Embarked`, `Survived`

#### 📌 Numerical Variables (Histograms)
- `Age`, `Fare`, `SibSp`, `Parch`

#### 📌 Correlation Heatmap
- Computed Pearson correlations for all numeric features.
- Visualized using a heatmap with annotations.

---

## 📈 Key Insights

- Majority of passengers were in **3rd class**, and most were **male**.
- **Southampton** was the most common embarkation port.
- Survival rate was **higher** for:
  - **Females**
  - **1st class passengers**
  - **Passengers who paid higher fares**
- Most people traveled **alone or with one relative**.
- Positive correlation observed between `Fare` and `Survived`.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **Seaborn**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📁 Project Structure

