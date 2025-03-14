# 📊 Predicting Bank Customer Churn Using Traditional vs. Advanced Machine Learning Models

## 📌 Overview
Customer churn, where customers stop using a bank's services, leads to **financial losses** and **customer retention challenges**. This project compares **Traditional Machine Learning models** (Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting) with **Deep Learning (Artificial Neural Networks - ANN)** to predict and mitigate churn effectively.

## 🚀 Project Goals
- 📌 **Analyze** a structured bank churn dataset with **115,640 customer records**.
- 📌 **Compare traditional ML models vs. ANN** in predicting churn.
- 📌 **Evaluate model fairness, explainability, and ethical concerns** in churn prediction.

## 📂 Dataset
- **Source:** Kaggle (Synthetic bank churn dataset)
- **Records:** 115,640 customers
- **Features:** Demographic, transactional, and behavioral indicators

## 🔍 Methodology
1. **📥 Data Preprocessing**
   - Cleaning, handling missing values, feature encoding & selection.

2. **📊 Exploratory Data Analysis (EDA)**
   - Visualizations to understand churn patterns across gender, education, income, and customer tenure.

3. **🤖 Machine Learning Model Training**
   - **Traditional Models:** Logistic Regression, Decision Tree, Random Forest, Gradient Boosting.
   - **Deep Learning:** ANN with **ReLU activations** and **Adam optimizer**.

4. **📈 Performance Evaluation**
   - **Accuracy, Precision, Recall, F1-score**
   - **Confusion Matrix for error analysis**
   - **Comparison of model performance**

## 📊 Results & Findings
| **Model**              | **Accuracy** | **Precision** | **Recall** | **F1-score** |
|------------------------|-------------|--------------|------------|-------------|
| Logistic Regression   | 97%         | 90%          | 81%        | 86%         |
| Decision Tree         | 100%        | 100%         | 100%       | 100%        |
| Random Forest        | 100%        | 100%         | 100%       | 100%        |
| Gradient Boosting     | 100%        | 100%         | 100%       | 100%        |
| ANN                  | 99%         | 98%          | 98%        | 98%         |

📌 **Observations:**
- **Tree-based models (DT, RF, GB) had perfect accuracy** but may be **overfitting**.
- **Logistic Regression struggled with recall (81%)**, meaning some churners were missed.
- **ANN performed well (99%)** and provided better generalization.

## 📌 Ethical Considerations
- **Bias & Fairness:** Checked for data imbalance to avoid unfair predictions.
- **GDPR Compliance:** Anonymized customer data to protect privacy.

## 🛠️ Technologies Used
- Python 🐍: `Scikit-Learn`, `TensorFlow`, `Matplotlib`, `Seaborn`
- Jupyter Notebook 📒: Data analysis and modeling
- Git & GitHub 🖥️: Version control and collaboration

## 📜 Acknowledgments
This project was structured with the assistance of **ChatGPT** for content refinement and **Canva** for visual presentations. AI tools were used to improve explanations, generate diagrams, and streamline model evaluation. All generated content was **validated for accuracy** and **aligned with research objectives**.

## 📌 Future Work
- 📌 Implement **Explainable AI (XAI)** to improve model interpretability.
- 📌 Explore **more deep learning models** for better performance.
- 📌 Apply the model on **real-world bank customer data**.

---

## 📥 Installation & Usage
To run this project locally:
```bash
# Clone the repository
git clone https://github.com/your-username/churn-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook

