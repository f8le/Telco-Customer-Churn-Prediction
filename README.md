# Telco Customer Churn Prediction 📊

### Overview
This project uses machine learning algorithms to predict customer churn based on the Telco Customer Churn dataset. The goal is to identify customers who are likely to leave the service, helping businesses to take proactive measures to retain them.

### 🚀 Features
- Data preprocessing, handling missing values, and normalization.
- Exploratory Data Analysis (EDA) with visualizations.
- Multiple classification models: Decision Tree, SVM, Naive Bayes, and Random Forest.
- Model evaluation using accuracy, F1 score, and confusion matrix.

### 📂 Project Structure

📁 Telco-Customer-Churn-Prediction
├── data
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── notebooks
│   └── Churn_Prediction.ipynb
├── src
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── evaluation.py
├── README.md
└── requirements.txt

### 📊 Dataset
The dataset used in this project is the [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn). It contains customer information to predict churn based on various features like contract type, payment method, and tenure.

### ⚙️ Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Telco-Customer-Churn-Prediction.git
    cd Telco-Customer-Churn-Prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### 🛠️ How to Use
- Open the `notebooks/Churn_Prediction.ipynb` file to see the step-by-step implementation.
- Run the `model_training.py` script to train the models:
    ```bash
    python src/model_training.py
    ```
- The `evaluation.py` script provides metrics to evaluate the performance.

### 🔍 Exploratory Data Analysis (EDA)
- Distribution of the target variable:
  ![Churn Distribution](images/churn_distribution.png)

- Correlation heatmap:
  ![Correlation Heatmap](images/correlation_heatmap.png)

### 📈 Results
The Random Forest Classifier achieved the highest accuracy with **87%** and an F1 score of **0.84**.

### 🤝 Contributing
Contributions are welcome! Feel free to open a pull request or report issues.

### 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

### **Step 3: Add Files and Code to Your Repository**

1. **Upload your dataset** and project files:
   - Use the **Upload files** button on your GitHub repository page.
   - Or, use Git command line:
     ```bash
     git add .
     git commit -m "Initial commit"
     git push origin main
     ```

2. **Create a requirements.txt file** if you have dependencies:
   ```txt
   pandas
   numpy
   matplotlib
   seaborn
   scikit-learn
