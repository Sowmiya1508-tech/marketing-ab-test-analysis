## 📊 Marketing Campaign A/B Test Analysis

## 📌 Business Problem

Companies invest heavily in advertisements, but often lack clear evidence of their effectiveness.
This project evaluates whether real advertisements drive higher conversions compared to Public Service Announcements (PSA), using large-scale user data and statistical testing.

## 🎯 Objective
Compare conversion performance: Ad vs PSA
Identify best days and hours for ad effectiveness
Analyze impact of ad exposure frequency
Provide data-driven business recommendations
## 📂 Dataset Overview
Total Users: 588,101
Groups:
Ad Group: 564,577
PSA Group: 23,524
Target Variable: Conversion (True/False)
Features: Day, Hour, Total Ads Seen, Group Type
## 🧪 Methodology
Data cleaning and preprocessing
Exploratory Data Analysis (EDA)
Group comparison (Ad vs PSA)
Conversion rate calculation
Contingency table creation
Chi-Square test for statistical significance
Confidence interval estimation
## 📊 Key Results
Metric	Value
Ad Conversion Rate	2.55%
PSA Conversion Rate	1.79%
Lift	+43.09%
Chi-Square Value	54.01
P-Value	< 0.001 (statistically significant)
Confidence Interval	2.51% – 2.60%
## 📈 Insights
📊 Ads outperform PSA by 43% higher conversion
📅 Best day: Monday (3.28%)
⏰ Best time: 2 PM – 5 PM (peak at 4 PM)
🌙 Worst performance: 1 AM – 3 AM
📢 Ad frequency strongly impacts conversion:
0–10 ads → 0.33%
100+ ads → 16.91%
⚖️ Similar ad exposure across groups → performance driven by content quality
## 📊 Visualizations

### 1. Conversion Rate — Ad vs PSA
![Conversion Rate](images/chart1_conversion_rate_ad_vs_psa.png)

### 2. Conversion Rate by Day of Week
![By Day](images/chart2_conversion_rate_day.png)

### 3. Conversion Rate by Hour
![By Hour](images/chart3_conversion_rate_hour.png)

### 4. Total Ads Distribution by Group
![Distribution](images/chart4_ads_distribution.png)

### 5. Conversion by Ad Volume Group
![Ad Volume](images/chart5_conversion_by_volume.png)

### 6. Statistical Summary Table
![Summary](images/statistical_summary_table.png)

## 💡 Business Recommendations
✅ Scale real ad campaigns
🎯 Focus on Monday & Tuesday
⏰ Run ads between 2 PM – 5 PM
📈 Increase ad exposure strategically
❌ Reduce PSA budget
🎨 Improve ad creative quality
## 💰 Business Impact
43% lift indicates strong ROI improvement potential
Optimized scheduling reduces wasted ad spend
Enables data-driven marketing decisions
## ⚠️ Limitations
Possible selection bias in user assignment
External factors (seasonality, campaigns) not included
High ad frequency may lead to user fatigue
## 🚀 Future Improvements
Apply logistic regression modeling
Perform advanced A/B testing simulations
Analyze long-term retention and churn
Segment users for deeper insights
## ⚙️ How to Run
git clone https://github.com/Sowmiya1508-tech/marketing-ab-test-analysis
cd marketing-ab-test-analysis

pip install -r requirements.txt

jupyter notebook
## 📂 Project Structure
marketing-ab-test-analysis/
│── data/
│     └── marketing_data.csv
│
│── images/
│     └── conversion_rate_ad_vs_psa.png
│      
│── notebooks/
│     └── Marketing A and B Test Analysis.ipynb
│
│── README.md
│── requirements.txt
## 🛠️ Tools & Technologies
Python (Pandas, NumPy)
Scipy (Chi-Square Test)
Statsmodels (Confidence Intervals)
Matplotlib & Seaborn (Visualization)
## 👩‍💻 Author

Sowmiya Devi
Aspiring Data Analyst
Skills: Python | SQL | Power BI
