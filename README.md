# 💓 Cardiotocographic Data Analysis - EDA Project

Welcome to this Exploratory Data Analysis (EDA) project on the **Cardiotocographic (CTG) dataset**, a powerful resource for understanding fetal health through monitoring of uterine contractions and fetal heart rate.

---

## 📊 Project Overview

This notebook (`eda1_assignment.ipynb`) performs a comprehensive exploratory analysis on the **Cardiotocographic dataset** to uncover patterns, identify anomalies, and understand the relationships between various features and fetal health conditions.

---

## 📁 Dataset Details

- **Filename**: `Cardiotocographic.csv`
- **Source**: UCI Machine Learning Repository
- **Records**: 2126 samples
- **Features**: 21 features including FHR baseline, accelerations, decelerations, uterine contractions, etc.
- **Target**: Fetal Health classification (`Normal`, `Suspect`, `Pathological`)

  **Dataset**:
  
- **LB** - Likely stands for "Baseline Fetal Heart Rate (FHR)" which represents the average fetal heart rate over a period.
- **AC** - Could represent "Accelerations" in the FHR. Accelerations are usually a sign of fetal well-being.
- **FM** - May indicate "Fetal Movements" detected by the monitor.
- **UC** - Likely denotes "Uterine Contractions", which can impact the FHR pattern.
- **DL** - Could stand for "Decelerations Late" with respect to uterine contractions, which can be a sign of fetal distress.
- **DS** - May represent "Decelerations Short" or decelerations of brief duration.
- **DP** - Could indicate "Decelerations Prolonged", or long-lasting decelerations.
- **ASTV** - Might refer to "Percentage of Time with Abnormal Short Term Variability" in the FHR.
- **MSTV** - Likely stands for "Mean Value of Short Term Variability" in the FHR.
- **ALTV** - Could represent "Percentage of Time with Abnormal Long Term Variability" in the FHR.
- **MLTV** - Might indicate "Mean Value of Long Term Variability" in the FHR.


---

## 🔍 Key EDA Highlights

- ✅ Null value analysis and data cleaning
- 📈 Descriptive statistics & distribution plots
- 🧠 Correlation heatmaps to identify influential features
- 📉 Boxplots & violin plots to detect outliers
- ⚖️ Class balance check for fetal health categories
- 🧪 Feature-wise comparisons for insights into abnormal vs normal cases

---

## 📎 Technologies Used

- Python s
- Jupyter Notebook 
- Libraries:
  - `pandas`, `numpy` for data manipulation
  - `matplotlib`, `seaborn` for visualization
  - `plotly` for interactive plots (if used)

---

## 🏁 How to Run this repository

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ctg-eda.git
