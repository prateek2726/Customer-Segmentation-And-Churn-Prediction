# 📊 Customer Segmentation and Churn Prediction

A Machine Learning project that predicts customer churn and segments customers based on their behavior using the **Telco Customer Churn Dataset**. The project applies **Exploratory Data Analysis (EDA)**, **Random Forest Classification**, and **K-Means Clustering** to generate actionable business insights.

🔗 **GitHub Repository:**
https://github.com/prateek2726/Customer-Segmentation-And-Churn-Prediction

---

# 📌 Project Overview

Customer retention is one of the most critical challenges for subscription-based businesses. This project aims to analyze customer data, identify factors that contribute to customer churn, and build a predictive model capable of identifying customers who are likely to leave. Additionally, customer segmentation is performed to group customers with similar characteristics, enabling businesses to develop targeted marketing and retention strategies.

---

# 🚀 Features

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Encoding
* Customer Churn Prediction
* Hyperparameter Tuning
* 5-Fold Cross Validation
* Customer Segmentation using K-Means
* Model Performance Evaluation

---

# 🛠️ Technologies Used

* Python
* Visual Studio Code
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains information such as:

* Customer Demographics
* Services Subscribed
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Internet Service
* Customer Tenure
* Churn Status

---

# 📊 Exploratory Data Analysis (EDA)

Various visualizations were used to understand customer behavior and identify important trends.

### Visualizations Used

* 📈 Histograms
* 📦 Box Plots
* 📊 Bar Plots
* 🔵 Scatter Plots
* 🔥 Correlation Heatmap
* 📉 Count Plots

These visualizations helped identify important features influencing customer churn and supported the feature engineering process.

---

# 🔄 Project Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Encoding
   │
   ▼
Train-Test Split
   │
   ▼
Random Forest Classifier
   │
   ▼
Hyperparameter Tuning
   │
   ▼
Cross Validation
   │
   ▼
Model Evaluation
   │
   ▼
Customer Segmentation (K-Means)
```

---

# 🤖 Machine Learning Models

## Customer Churn Prediction

* Random Forest Classifier
* Hyperparameter Tuning
* Cross Validation

## Customer Segmentation

* StandardScaler
* K-Means Clustering
* Elbow Method

---

# 📈 Model Performance

## Best Model Performance

| Metric    | Score      |
| --------- | ---------- |
| Accuracy  | **71.32%** |
| Recall    | **85.50%** |
| Precision | **49.70%** |
| F1 Score  | **62.87%** |

---

## 5-Fold Cross Validation

### Accuracy

```
Fold 1 : 75.23%
Fold 2 : 78.50%
Fold 3 : 75.02%
Fold 4 : 77.20%
Fold 5 : 76.70%

Mean Accuracy : 76.53%
```

### Recall

```
Fold 1 : 72.99%
Fold 2 : 80.48%
Fold 3 : 76.20%
Fold 4 : 78.34%
Fold 5 : 73.46%

Mean Recall : 76.30%
```

The model was optimized with a focus on **Recall**, ensuring that customers likely to churn are correctly identified, which is especially important for customer retention strategies.

---

# 📁 Repository Structure

```text
Customer-Segmentation-And-Churn-Prediction/
│
├── Customer Segmentation And Churn Prediction.ipynb
├── Telco_customer_churn.xlsx
├── README.md
```

---

# ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/prateek2726/Customer-Segmentation-And-Churn-Prediction.git
```

### 2. Navigate to the Project Folder

```bash
cd Customer-Segmentation-And-Churn-Prediction
```

### 3. Create a Virtual Environment (Recommended)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### 5. Open the Project in VS Code

```bash
code .
```

### 6. Select the Python Interpreter

* Press **Ctrl + Shift + P**
* Type **Python: Select Interpreter**
* Choose the virtual environment you created

### 7. Run the Notebook

Open `Customer Segmentation And Churn Prediction.ipynb` in VS Code and click **Run All** (or execute cells individually using the Jupyter extension).

---

# 📌 Key Insights

* Customers with shorter tenure are more likely to churn.
* Contract type significantly influences customer retention.
* Monthly charges have a strong relationship with churn probability.
* Customer segmentation enables businesses to create personalized marketing strategies.

---

# 👨‍💻 Author

**Prateek Rathore**

GitHub: https://github.com/prateek2726

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub!
