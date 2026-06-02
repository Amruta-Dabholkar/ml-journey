# 🚀 ML Learning Journey

> A structured repository documenting my self-driven learning journey in Python, Statistics, and Machine Learning.

---

## 👩‍💻 About Me

**Amruta Dabholkar** — 3rd Year Computer Engineering Student passionate about Data Science & AI.
I believe in learning by doing — every concept I study gets coded, committed, and pushed here.

🌍 Building in public, one commit at a time.

---

## 📁 Repository Structure

```
ml-journey/
│
├── PYTHON REVISION/          # Python fundamentals & examples
│   ├── PYTHON_EXAMPLES_PART1.ipynb
│   ├── PYTHON_EXAMPLES_PART2.ipynb
│   ├── PYTHON_EXAMPLES_PART3.ipynb
│   └── PYTHON_EXAMPLES_PART4.ipynb
│
├── Stats/                    # Statistical tests & analysis
│   ├── t_test.ipynb
│   ├── two_sample_test.ipynb
│   ├── Z-TEST.ipynb
│   ├── annova_test.ipynb
│   ├── chi_square_test.ipynb
│   └── outliers.ipynb
│
├── numpy/                    # NumPy practice
│
├── ml-part1/                 # ML Part 1 - EDA & Preprocessing
│   └── insurance_eda.ipynb
│
├── data/
│   └── insurance.csv
│
└── README.md
```

---

## 🐍 Python Revision

**Files:** `PYTHON REVISION/`

Topics covered:
- Variables, data types (int, float, bool, None, complex)
- Type conversion & string methods
- f-strings
- Arithmetic, comparison, logical & assignment operators
- Identity and membership operators
- Input / Output
- If-else, elif chains, nested if, ternary operator
- Practical examples: BMI calculator, login system, calculator
- While loops, mini-game logic
- Dictionaries — key-value pairs, methods, iteration

---

## 📊 Statistics

**Files:** `Stats/`

| File | Topic | Dataset | Result |
|------|-------|---------|--------|
| `t_test.ipynb` | One Sample T-Test | Custom height data | Accept H₀ |
| `two_sample_test.ipynb` | Two Sample T-Test | Group A vs B scores | Reject H₀ |
| `Z-TEST.ipynb` | Z-Test | Custom height data | Accept H₀ |
| `annova_test.ipynb` | ANOVA Test | Titanic (age vs pclass) | Reject H₀ — significant age difference across classes |
| `chi_square_test.ipynb` | Chi-Square Test | Titanic (gender vs survival) | Reject H₀ — gender significantly affects survival |
| `outliers.ipynb` | Outlier Detection | Custom dataset | IQR & Z-score methods |

**Key concepts practiced:** Null hypothesis, p-value, alpha = 0.05, degrees of freedom, f-statistic, chi2 statistic, contingency tables.

---

## 🔢 NumPy

**Files:** `numpy/`

Topics covered:
- Array creation, reshaping, indexing, slicing
- Broadcasting
- Mathematical operations
- Statistical functions (mean, std, var)

---

## 🤖 Machine Learning

### ML Part 1 — Insurance EDA & Preprocessing

**File:** `ml-part1/insurance_eda.ipynb`
**Dataset:** `data/insurance.csv`

Topics covered:
- Exploratory Data Analysis (EDA) — histplot, boxplot, countplot, heatmap
- Data cleaning — removing duplicates, checking nulls
- Encoding — binary mapping (`sex`, `smoker`), one-hot encoding (`region`)
- Feature engineering — BMI categories using `pd.cut()`
- Feature scaling — StandardScaler on numeric columns
- Feature selection:
  - Pearson Correlation (numerical features vs charges)
  - Chi-Squared Test (categorical features vs binned charges)
- Final selected features: `age`, `bmi`, `is_smoker`, `is_female`, `children`, `region_southeast`, `bmi_category_Obese`

---

## 📈 Progress Tracker

| Topic | Status |
|-------|--------|
| Python Basics | ✅ Done |
| Python Conditionals | ✅ Done |
| While Loop & Mini Game | ✅ Done |
| Dictionary | ✅ Done |
| OOP | 🔄 In Progress |
| Basic Probability | ✅ Done |
| Two Sample Test | ✅ Done |
| Covariance & Correlation | ✅ Done |
| Statistical Tests (T, Z, ANOVA, Chi-Square) | ✅ Done |
| Outlier Detection | ✅ Done |
| Pandas | ✅ Done |
| NumPy | ✅ Done |
| Data Visualization | 🔄 In Progress |
| ML Part 1 — EDA & Preprocessing | ✅ Done |
| ML Part 2 | 🔜 Upcoming |
| ML Part 3 | 🔜 Upcoming |
| ML Part 4 | 🔜 Upcoming |

---

## 🛠️ Libraries Used

```python
numpy       pandas      matplotlib
seaborn     scipy       sklearn
```

---

## 🌱 Daily Habit

- 📝 Study 2 topics daily (2 hrs each)
- 💻 Code every concept, don't just read
- 🟩 Push to GitHub every single day
- 🔗 Document progress on LinkedIn

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amruta_Dabholkar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/amruta-dabholkar)
[![GitHub](https://img.shields.io/badge/GitHub-Amruta--Dabholkar-black?style=flat&logo=github)](https://github.com/Amruta-Dabholkar)

---

*"Consistency beats intensity. 2 hours daily beats 10 hours once a week."* 🔥
