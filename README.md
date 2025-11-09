# 🧱 Concrete Quality Analysis / تحلیل کیفیت بتن

**Concrete Quality Analysis**  A Streamlit based machine learning dashboard for predicting concrete compressive strength (MPa) using compositional parameters such as water-cement ratio, aggregates, and admixtures.  
یک داشبورد یادگیری ماشین مبتنی بر Streamlit برای پیش‌بینی مقاومت فشاری بتن (MPa) با استفاده از پارامترهای ترکیبی مانند نسبت آب به سیمان، مصالح ریز و درشت و افزودنی‌ها.

---

## 🔬 Features / ویژگی‌ها

- Data upload and preprocessing (CSV/Excel) / آپلود داده و پیش‌پردازش (CSV/Excel)  
- Correlation heatmap of variables / نمودار همبستگی متغیرها  
- ML model training and evaluation / آموزش و ارزیابی مدل‌های ML  
- Streamlit dashboard with dynamic plots / داشبورد Streamlit با نمودارهای پویا  
- Persian-English dual UI / رابط دو زبانه فارسی و انگلیسی  
- Export of prediction results / خروجی نتایج پیش‌بینی

---

## 📁 Project Structure / ساختار پروژه

concrete-quality-analysis/
├── src/
│ ├── data_loader.py # Data loading & preprocessing / بارگذاری و پیش‌پردازش داده
│ ├── analysis.py # ML model training & evaluation / آموزش و ارزیابی مدل ML
│ └── visualization.py # Dynamic plots & visualizations / نمودارها و بصری‌سازی
├── docs/
│ └── architecture.png # Architecture diagram / نمودار معماری
├── tests/ # Unit and integration tests / تست‌ها
├── requirements.txt # Python dependencies / پیش‌نیازهای پایتون
├── pyproject.toml
├── LICENSE
├── README.md
├── .github/
│ ├── ISSUE_TEMPLATE/
│ │ ├── bug_report.md
│ │ └── feature_request.md
│ └── PULL_REQUEST_TEMPLATE.md
├── CONTRIBUTING.md
└── SECURITY.md


---

## ⚙️ Requirements / پیش‌نیازها

- Python ≥ 3.10  
- Main libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `streamlit`

```bash
pip install -r requirements.txt

🚀 Installation & Running / نصب و اجرا

Step 1 / مرحله ۱: Clone repository / کلون کردن مخزن

git clone https://github.com/shahpari2kht/concrete-quality-analysis.git
cd concrete-quality-analysis


Step 2 / مرحله ۲: Setup virtual environment (optional but recommended)

# Linux / macOS
python3 -m venv venv
source venv/bin/activate

# Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1


Step 3 / مرحله ۳: Install dependencies / نصب پیش‌نیازها

pip install -r requirements.txt


Step 4 / مرحله ۴: Run Streamlit dashboard / اجرای داشبورد Streamlit

streamlit run src/visualization.py

📈 ML Objective / هدف ML

Predict concrete compressive strength from material composition:
پیش‌بینی مقاومت فشاری بتن با استفاده از ترکیب مواد:

fc​=f(CW​,aggregate%, admixture%, age)​

,aggregate%, admixture%, age)
🧠 Key Learnings / نکات کلیدی

End-to-end ML pipeline / مسیر کامل ML

Data preprocessing & feature engineering / پیش‌پردازش داده و مهندسی ویژگی‌ها

Model comparison (RandomForest, XGBoost) / مقایسه مدل‌ها

Interactive dashboards with Streamlit / داشبورد تعاملی

Dual-language support / پشتیبانی دو زبانه

👩‍💻 Author / نویسنده

Parisa Mohammadzadeh – Data Scientist & Developer / دانشمند داده و توسعه‌دهنده
📍 Iran / ایران
📧 shahpari2kht@gmail.com

🔗 GitHub Profile

🔒 Security Notes / نکات امنیتی

Do not commit private keys or sensitive data / توکن‌ها و داده‌های حساس هرگز اضافه نشوند

Sample files are only placeholders / فایل‌های نمونه فقط مقادیر نمایشی دارند

All critical configurations are stored privately / تنظیمات مهم به صورت خصوصی نگهداری می‌شوند
