# 📊 Institutional Research & Innovation Evaluation Analysis

## 📝 Project Overview
This project analyzes institutional research performance based on the AQUA evaluation framework. It integrates both quantitative data from `data.csv` and qualitative insights from `[AQUA] Rapport.pdf`.

---

## 💁️ Project Structure

| File/Folder          | Description                                      |
|----------------------|--------------------------------------------------|
| `data.csv`           | Dataset containing evaluation criteria & scores  |
| `[AQUA] Rapport.pdf` | Official evaluation report (French)              |
| `dataAnalysis.ipynb` | Main script for data processing and analysis     |

---

## ⚙️ Technical Requirements

- **Python 3.8+**
- Install required libraries:
  ```bash
  pip install pandas matplotlib seaborn wordcloud
  ```

---

## 🔍 Key Analysis Features

### 1️⃣ Data Preprocessing
- Convert percentages (e.g., `85% → 0.85`)
- Handle missing values
- Check for duplicate entries

### 2️⃣ Core Analytics
- **Descriptive Statistics**:
  - Score distribution analysis
  - Identification of top/bottom 5 criteria
- **Visualizations**:
  - Box plots per domain (R1/R2/R3)
  - Heatmaps of reference performance
  - Word cloud from remarks
- **Correlation Analysis**:
  - Relationship between domains, references, and scores

### 3️⃣ Critical Insights
- Identify weak criteria (<50% score)
- Compare performance between domains

---

## 📈 Key Findings (From Report)

- **Overall Score:** `74.79%`
- **Strongest Domain:** `R1 (Structuration/Organization)`
- **Critical Weaknesses:**
  - Lack of communication strategy
  - Absence of a centralized publication platform
  - Limited student engagement activities

---

## 🚀 How to Run

### 1️⃣ Install dependencies:
```bash
pip install pandas matplotlib seaborn wordcloud
```

### 2️⃣ Open Jupyter Notebook:
```bash
jupyter notebook dataAnalysis.ipynb
```

### 3️⃣ Execute the notebook:
Run all cells inside `dataAnalysis.ipynb` to generate results and visualizations.

### 4️⃣ View outputs:
Check the `visualizations/` folder for generated charts.

---

## 📄 Documentation Links
- [LCSI Official Website](#)
- [Evaluation Framework Documentation](#)

---

## 👥 Maintainers
- **[Achraf Abdelkebir]** | 📧 [la_abdelkebir@esi.dz]

## 4️⃣ License
This project is licensed under the **MIT License**.

