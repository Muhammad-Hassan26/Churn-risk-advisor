📊 Churn Risk Advisor

An interactive, machine learning-driven web application designed to predict customer churn risk for telecommunications services[cite: 2, 3]. Built using an optimized XGBoost model and deployed via Streamlit Community Cloud, this tool provides both real-time individual risk assessments and large-scale batch scoring capabilities.
 
📁 GitHub Repository: [Muhammad-Hassan26/churn-risk-advisor](https://github.com/Muhammad-Hassan26/churn-risk-advisor)

---

## 🌟 Key Features

* **Real-time Single Customer Assessment:** Interactively adjust customer demographic and subscription parameters to instantly view churn probability and risk bands (Low, Moderate, High)[cite: 3].
* **Batch Scoring Capability:** Upload CSV datasets (e.g., `sample_customers.csv`) to process up to 50 customer profiles simultaneously with instant risk tiering and downloadable results[cite: 3, 10].
* **Actionable Retention Recommendations:** Automatically provides strategic recommendations and intervention strategies based on predicted churn probabilities[cite: 3].
* **XGBoost ML Engine:** Powered by a pre-trained XGBoost 2.0.3 classifier for accurate probability estimates[cite: 3, 7].

---

## 🛠️ Tech Stack

* **Language:** Python 3.12
* **Web Framework:** Streamlit
* **Machine Learning Engine:** XGBoost (2.0.3) & Scikit-Learn (1.6.1)[cite: 4, 7]
* **Data Processing & Analytics:** Pandas & NumPy[cite: 7]
* **Model Serialization:** Joblib[cite: 4, 7]

---

## 📁 Repository Structure

```text
churn-risk-advisor/
├── app.py                  # Main Streamlit application entry point
├── churn_model.joblib      # Pre-trained XGBoost model artifact
├── model_meta.json         # Feature list and metadata specification
├── sample_customers.csv    # Sample batch input dataset for testing
├── requirements.txt        # Python dependency specifications
└── README.md               # Project documentation
