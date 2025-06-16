# 🧠 ML-Based Early Detection of Cardiac Arrest in Newborns (CICU)

This project explores the use of Machine Learning and statistical modeling to enable early detection of cardiac arrest in newborn babies admitted to the Cardiac Intensive Care Unit (CICU). The goal is to provide a proactive, data-driven approach to monitoring critical health indicators and supporting timely medical intervention.

## 🚀 Objective

To develop a predictive model that can:
- Monitor vital signs in real-time
- Identify patterns leading up to cardiac arrest
- Alert medical staff ahead of time to reduce response latency

## 📊 Dataset

The dataset consists of anonymized CICU patient data, including:
- Heart rate
- Respiratory rate
- Oxygen saturation (SpO2)
- Blood pressure
- Temperature
- Time-stamped medical events

> **Note:** Data is simulated or collected from publicly available medical datasets (e.g., PhysioNet) due to privacy concerns.

## 🧪 Methods & Technologies

- **Languages:** Python
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn
- **ML Models:**
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - XGBoost
- **Statistical Techniques:**
  - Feature selection
  - Time-series analysis
  - Outlier detection
- **Evaluation Metrics:**
  - Accuracy, Precision, Recall
  - ROC-AUC
  - Confusion Matrix

## 🔄 Workflow

1. **Data Preprocessing**
   - Handling missing values
   - Time alignment and smoothing
   - Feature engineering

2. **Model Training & Validation**
   - Train/test split
   - Cross-validation
   - Hyperparameter tuning

3. **Performance Evaluation**
   - Compare model accuracy and sensitivity
   - Visualize ROC curves and feature importance

4. **Deployment (Optional)**
   - Prototype a web app using Streamlit for demo purposes

## 💡 Key Insights

- Early physiological signals can help predict cardiac risk within 30–60 minutes before the event.
- Ensemble models like Random Forest showed better sensitivity than linear models.
- Proper feature engineering from time-series data significantly boosts prediction quality.

## 🏥 Impact

An accurate and early warning system could:
- Improve survival rates in newborns
- Reduce strain on CICU staff
- Enhance clinical decision-making with real-time alerts

## 🔐 Ethics & Privacy

- No real patient data was used without permission.
- The project follows ethical guidelines for data handling and model fairness.

## 📂 Folder Structure

├── data/ # Raw & processed data files
├── notebooks/ # Jupyter notebooks for EDA & modeling
├── models/ # Saved trained models
├── app/ # (Optional) Streamlit app files
├── reports/ # Results, graphs, and evaluation
└── README.md  


## 👨‍💻 Author

Chandramouli Bogala  
*Python Full Stack Developer | Data & ML Enthusiast*

## 📬 Contact

Feel free to reach out for collaboration, feedback, or research:
📧 [chandramoulibogala43@gmail.com]  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/chandramouli23/)

---

> ⚠️ *Disclaimer: This project is for educational and research purposes only. It is not intended for clinical use without proper medical validation.*

