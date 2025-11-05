# Concrete Quality Analysis 🧱

A Streamlit-based machine learning dashboard for predicting concrete **compressive strength (MPa)** using compositional parameters such as water-cement ratio, fine/coarse aggregates, and admixtures.  
Developed for exploratory data analysis, model comparison (RandomForest, XGBoost), and visualization of feature impact.

---

## 🔬 Features
- Data upload and preprocessing (CSV/Excel)
- Correlation heatmap of variables
- ML model training and evaluation
- Streamlit dashboard with dynamic plots
- Persian-English interface support (dual UI)
- Export of prediction results

---

## 🧩 Project Structure
concrete-quality-analysis/

├── src/

│ ├── data_loader.py

│ ├── analysis.py

│ └── visualization.py

├── tests/

├── requirements.txt

├── pyproject.toml

├── docs/

│ └── architecture.png

├── LICENSE

└── README.md


## ⚙️ Requirements
Python ≥ 3.10  
Main libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `streamlit`
```bash
pip install -r requirements.txt
📈 ML Objective
Predict concrete compressive strength from material composition:

[

f_c = f\left(\frac{W}{C}, \text{aggregate%, admixture%, age}\right)

]

🧠 Author
Parisa Mohammadzadeh – Data Scientist

📬 shahpari2kht@gmail.com

🔗 GitHub Profile
