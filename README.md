# 🧬 Huntington's Disease — Data Analysis & Preprocessing

Exploratory data analysis and preprocessing pipeline on a Huntington's Disease clinical dataset, preparing the data for machine learning with feature scaling, encoding, and class balancing techniques.

## 📊 Project Workflow

1. **Data Cleaning** — Duplicate removal & dropping irrelevant columns (Patient ID, random sequences)
2. **Missing Value Handling** — Mode imputation for categorical, median for numerical features
3. **Label Encoding** — Converting categorical columns to numeric values
4. **Standardization** — Feature scaling using StandardScaler
5. **Correlation Analysis** — Heatmap of feature relationships
6. **Outlier Detection & Removal** — IQR method with before/after boxplots (Chorea Score)
7. **Data Visualization**
   - Violin plot: CAG Repeats across disease stages
   - Pair plot: Clinical metrics relationships by disease stage
   - KDE joint plot: CAG Repeats vs Age density mapping
8. **Class Balancing** — SMOTE, TomekLinks & SMOTETomek techniques (imbalanced-learn)

## 🛠️ Tech Stack

- **Language:** Python
- **Environment:** Jupyter Notebook (Anaconda)
- **Libraries:** Pandas, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn

## 🚀 How to Run

1. Clone this repository
2. Install requirements: `pip install pandas matplotlib seaborn scikit-learn imbalanced-learn`
3. Open the notebook in Jupyter Notebook
4. Run all cells

## 👩‍💻 Author

**Ashna Usmani**
GitHub: [@ashnausmanii](https://github.com/ashnausmanii)
