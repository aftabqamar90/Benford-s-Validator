# Benford's Law Analytics Dashboard 🔍📊

A modern, interactive **Benford’s Law Validator** built with **HTML, Tailwind CSS, and Chart.js**.  
This dashboard helps identify anomalies and potential fraud patterns in numerical datasets using **Benford’s Law statistical analysis**.

---

## 🚀 Features

- ✅ Paste raw numerical data or upload files (`.csv`, `.txt`, `.json`)
- 📈 Automatic Benford’s Law validation
- 🧮 Statistical metrics:
  - Chi-Square Test
  - Z-Scores
  - Maximum Deviation
- 📊 Rich visualizations:
  - Bar Chart (Observed vs Expected)
  - Radar Chart
  - Cumulative Line Chart
  - Trend Line
  - Z-Score Anomaly Chart
  - Deviation Chart
  - Doughnut Chart
- ⚡ Handles **up to 2 million records**
- 🎲 Built-in **Log-Normal Sample Data Generator**
- 🌙 Dark-mode optimized forensic dashboard UI

---

## 🧠 What Is Benford’s Law?

Benford’s Law states that in many naturally occurring datasets, the leading digit **1** appears about **30%** of the time, while larger digits occur less frequently.  
This property is widely used in:
- Fraud detection
- Financial auditing
- Forensic accounting
- Data integrity validation

---

## 🛠️ Technology Stack

- **HTML5**
- **Tailwind CSS** (UI & styling)
- **Chart.js** (data visualization)
- **Vanilla JavaScript** (logic & statistics)

No backend or database required.

---

## 📂 Supported Input Formats

- CSV (comma-separated)
- Space-separated values
- Line-separated values
- JSON (numbers extracted automatically)

---

## ▶️ How to Use

1. Open `index.html` in your browser  
2. Choose one of the following:
   - Paste numerical data
   - Upload a data file
   - Generate sample data
3. Click **Run Analysis**
4. Review charts, statistics, and verdict

---

## 📐 Statistical Verdict Logic

- **Chi-Square Threshold:** `15.507`
- **Z-Score Alert:** `|Z| > 2`
- **Verdict Output:**
  - ✅ **VALID** → Matches Benford’s distribution
  - 🚨 **ANOMALY** → Potential manipulation or irregularity

---

## 📸 Screenshots

> Add screenshots here for better presentation  
> Example:
