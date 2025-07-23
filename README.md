# PRODIGY_DS_03 

- Bank Marketing Campaign Analysis

## 📌 Project Overview

This project uses the **Bank Marketing dataset** from the UCI Machine Learning Repository to uncover insights into customer behavior and predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data.

The aim is to build a **Decision Tree Classifier** to:
- Identify key patterns in customer responses.
- Predict campaign success.
- Assist marketers in targeting the right audience efficiently.

---

## 📂 Dataset

- **Source**: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Contents**: Demographic, contact, and campaign-related information for marketing calls.

---

## 🧠 Machine Learning Workflow

1. **Data Loading & Preprocessing**
   - Handled missing values and encoded categorical variables.
   - Normalized/standardized numerical columns.

2. **Model Building**
   - Implemented a **Decision Tree Classifier** using `scikit-learn`.
   - Tuned hyperparameters (e.g., `max_depth`, `criterion`) to improve performance.

3. **Evaluation**
   - Accuracy, Confusion Matrix, Classification Report.
   - Visualized the decision tree for interpretation.

4. **Insights**
   - Identified factors influencing customer decision-making.
   - Explored customer profiles with high conversion rates.

---

## 📊 Key Results

- Achieved solid predictive performance using a simple and interpretable model.
- Key influencing features: `contact type`, `previous outcome`, `duration`, `job`, and `month`.

---

## 📝 File Structure

```bash
├── bank+marketing/               # Folder containing raw CSV data
├── Task_3.ipynb                  # Jupyter Notebook with complete implementation
├── README.md                     # Project README

---

🚀 How to Run : 
    git clone https://github.com/YugalSoni/PRODIGY_DS_03.git
  cd PRODIGY_DS_03

---

🔍 Future Improvements

Try other models like Random Forest or Gradient Boosting.
Deploy the model using Flask/Streamlit.
Build a dashboard to monitor campaign success.

