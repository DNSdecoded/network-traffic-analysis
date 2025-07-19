# 📊 Internet Usage Analysis

This project analyzes internet usage data from an ISP log file (`isp.csv`) to uncover session behavior, peak usage times, daily/hourly trends, anomalies, and more. It includes data preprocessing, insightful analytics, and visualizations.

---

## 📁 Dataset

**Input File:** `isp.csv`

Each row in the dataset contains:
- `MAC Id`: Device identifier
- `Login Time`: Session start time
- `Session Time`: Duration of the session (HH:MM:SS)
- `Download`: Data downloaded in MB
- `Upload`: Data uploaded in MB

---

## 🧪 Objectives

- Load and clean the dataset
- Engineer useful time-based features
- Analyze total download/upload, sessions, and durations
- Identify top usage days and active hours
- Compare weekday vs weekend usage
- Detect anomalies (long sessions, rapid relogins, high data usage)
- Visualize trends and insights
- Generate a summary report

---

## 📊 Key Insights Extracted

- 📦 **Total Download**: ~935 GB  
- 🚀 **Total Upload**: ~68 GB  
- 📈 **Total Sessions**: 1163  
- 🕒 **Average Session Duration**: ~29.27 minutes  
- 💡 **Peak Download Day**: 2025-06-17 (~102.78 GB)  
- 🔼 **Upload/Download Ratio**: ~0.07  
- ⏱ **Longest Session**: 61.48 minutes  
- ⚡ **Shortest Session**: 0 minutes (rapid relogin)  

---

## 📊 Visualizations

- 📅 **Line plot**: Daily download/upload trends
- 📊 **Bar chart**: Top 5 usage days
- 🧊 **Heatmap**: Hourly login distribution by weekday
- 📉 **Histogram**: Session time distribution
- 🥧 **Pie chart**: Upload vs Download share
- 📈 **Cumulative usage plot**: Over time
- 📆 **Daily session duration**: Trend over the month

---

## 🧰 Tools Used

- `pandas` – data processing
- `matplotlib` / `seaborn` – data visualization
- `numpy` – numerical computations
- `jupyter notebook` – analysis interface

---

## 📦 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/internet-usage-analysis.git
   cd internet-usage-analysis
