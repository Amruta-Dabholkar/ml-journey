# 🚀 ML Learning Journey

A personal repository documenting my learning journey in Python, Machine Learning, and Statistics.

---

## 📁 Repository Structure

```
ml-journey/
├── python-revision/
│   └── PYTHON_EXAMPLES.ipynb       # Python basics to conditionals
├── ml-part1/
│   └── insurance_eda.ipynb         # EDA, preprocessing, feature engineering
├── data/
│   └── insurance.csv               # Dataset used for ML Part 1
└── README.md
```

---

## 📘 Python Revision

**File:** `python-revision/PYTHON_EXAMPLES.ipynb`

Topics covered:
- Variables, data types (int, float, bool, None, complex)
- Type conversion
- Strings and string methods
- f-strings
- Arithmetic, comparison, logical, assignment operators
- Identity and membership operators
- Input / Output
- If-else, elif chains, nested if, ternary operator
- Practical examples: BMI calculator, login system, calculator

---

## 📊 ML Part 1 — Insurance EDA & Preprocessing

**File:** `ml-part1/insurance_eda.ipynb`  
**Dataset:** `data/insurance.csv`

Topics covered:
- Exploratory Data Analysis (EDA) — histplot, boxplot, countplot, heatmap
- Data cleaning — removing duplicates, checking nulls
- Encoding — binary mapping (`sex`, `smoker`), one-hot encoding (`region`)
- Feature engineering — BMI categories using `pd.cut()`
- Feature scaling — `StandardScaler` on numeric columns
- Feature selection:
  - Pearson Correlation (numerical features vs charges)
  - Chi-Squared Test (categorical features vs binned charges)
- Final selected features: `age`, `bmi`, `is_smoker`, `is_female`, `children`, `region_southeast`, `bmi_category_Obese`

---

## 🛠️ Libraries Used

```
numpy, pandas, matplotlib, seaborn, scikit-learn, scipy
```

---

## 📈 Progress

| Topic | Status |
|---|---|
| Python Basics | ✅ Done |
| Python Conditionals | ✅ Done |
| EDA & Preprocessing | ✅ Done |
| Feature Engineering | ✅ Done |
| ML Models | 🔄 In Progress |
| Statistics | 🔄 In Progress |

---

