# 🚨 Anomaly Detection in Operational Metrics

### 📌 Overview
This project applies unsupervised learning techniques to detect anomalies in customer support metrics (e.g., SLA %, Handling Time) using time series data — mimicking real-world trust & safety operations.

---

### 🧪 Methodology
- Synthetic data simulation with injected anomalies (ground truth)
- Univariate and multivariate anomaly detection:
  - **Z-Score**
  - **Isolation Forest**
  - **Local Outlier Factor (LOF)**
- Advanced forecasting-based detection using:
  - **Facebook Prophet**

---

### 📊 Visual Analysis
- Interactive line plots and rolling averages to visualize trends
- Residual-based anomaly detection from Prophet forecast bounds

---

### 🧰 Tools Used
- Python (Pandas, Scikit-learn, Prophet, Seaborn, Plotly)
- Jupyter Notebook

---

### 🎯 Value Delivered
- Enables proactive identification of SLA or staffing issues
- Helps ops teams react to performance drops before escalation
- Supports data-driven decision making in support orgs

---

### ✅ Next Steps
- Try LSTM/Autoencoders for deeper anomaly detection
- Integrate with a live dashboard using Streamlit or Dash
