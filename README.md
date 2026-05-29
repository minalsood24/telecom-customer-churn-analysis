# Telco Customer Churn Analysis

## 📌 Project Overview
Customer churn is a critical challenge for subscription-based telecom companies. This project analyzes customer behavior to identify the key drivers of churn and provides actionable business recommendations to reduce customer attrition.

**Goal** → Uncover patterns in churned customers and suggest data-driven retention strategies.

## 🎯 Business Problem
A telecom company is experiencing high customer churn. The business needs to understand:
- Which customer segments are most likely to leave?
- What service/contract features correlate with churn?
- How can the company proactively retain high-risk customers?

## 🧰 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook** (for interactive analysis)
- **Git & GitHub** (version control)

## 📁 Dataset
- Source: [IBM Telco Customer Churn dataset](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm) (publicly available)
- Records: ~7,000 customers
- Features: Demographics, account information, services subscribed, and churn label

## 🔍 Methodology
1. **Data Cleaning** – Handled missing values (e.g., `TotalCharges` converted to numeric), removed duplicates.
2. **Exploratory Data Analysis (EDA)** – Visualized churn distribution, contract types, payment methods, tenure, monthly charges.
3. **Correlation Analysis** – Identified features with the strongest relationship to churn.
4. **Insights Extraction** – Translated findings into business recommendations.

## 📊 Key Insights (with visual evidence)
| Insight | Data Finding | Business Implication |
|---------|--------------|------------------------|
| **Month-to-month contracts** | ~45% churn rate vs. ~10% for long-term contracts | Convert monthly customers to 1‑ or 2‑year plans with small incentives |
| **High monthly charges** | Churn probability increases by ~15% when charges > $70 | Offer loyalty discounts or bundled packages for high‑value customers |
| **No online security / tech support** | Churn rate 2x higher among customers without these services | Bundle these services for free in the first 3 months |
| **Electronic check payment** | Churn rate ~50% – highest among all methods | Promote auto‑pay / credit card with a 2% monthly discount |

https://github.com/minalsood24/teleco-churn-analysis/tree/main/Screenshots 
refer here for the images of the project


## 💡 Recommendations for the Telecom Company
- **Retention campaign** targeting month‑to‑month customers (e.g., upgrade discount, loyalty bonus).
- **Price sensitivity program** – identify customers paying > $70/month and offer a tailored bundle.
- **Proactive service education** – promote security add‑ons for customers who currently lack them.
- **Payment method migration** – incentivize switching from electronic check to autopay.

## 🚀 How to Reproduce This Analysis
1. Clone the repository  
   git clone https://github.com/minalsood24/teleco-churn-analysis.git
   
2.Install required libraries

pip install pandas numpy matplotlib seaborn jupyter

3.Open the Jupyter notebook

jupyter notebook telco_churn_analysis.ipynb
Run cells sequentially.

📈 Future Improvements
Build a predictive model (Logistic Regression / Random Forest) to flag high‑risk customers in real time.

Create an interactive dashboard using Tableau or Power BI.

Segment customers using clustering (K‑means) for hyper‑targeted retention offers.

👩‍💻 About the Author
Minal Sood – MSc IT student (Data Analytics curriculum, 2nd semester). Passionate about turning data into business decisions.
Prabhleen Kaur - MSc IT student (Data Analytics curriculum, 2nd semester). Passionate about turning data into business decisions.
📫 LinkedIn (www.linkedin.com/in/minal-sood24)
🐙 GitHub

📃 License
This project is for educational portfolio purposes only.
