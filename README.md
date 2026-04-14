# Marketing Campaign A/B Test Analysis
### Python | Statistics | Data Visualization

## 📌 Project Overview
Analyzed 588,101 user records to evaluate whether 
a real advertisement performs better than a Public 
Service Announcement (PSA) in converting users to customers.

---

## 🎯 Objective
- Test if real ads cause more conversions than PSA
- Identify best performing days and hours for ads
- Understand impact of ad frequency on conversion
- Provide statistical proof for business decisions

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|---|---|
| Python (Pandas, Numpy) | Data loading and cleaning |
| Scipy | Chi-Square statistical test |
| Statsmodels | Confidence Interval calculation |
| Matplotlib & Seaborn | Data visualization |

---

## 📂 Dataset
- **Records:** 588,101 users
- **Columns:** 7
- **Groups:** ad (564,577 users) vs psa (23,524 users)
- **Target:** Converted (True/False)

---

## 📊 Statistical Analysis

| Metric | Value |
|---|---|
| Ad Conversion Rate | 2.55% |
| PSA Conversion Rate | 1.79% |
| Chi-Square Value | 54.0058 |
| P-Value | 0.0 (< 0.05) |
| Lift | 43.09% |
| Confidence Interval | 2.51% to 2.60% |

---

## 💡 Key Insights
1. Ad campaign is **statistically proven** to work
   P-value = 0.0 confirms difference is not random
2. Real ad performs **43% better** than PSA group
   Ad: 2.55% vs PSA: 1.79% conversion rate
3. **Monday** has highest conversion rate at 3.28%
   Weekdays outperform weekends consistently
4. **Hour 16 (4PM)** has peak conversion at 3.08%
   Early morning hours (1-3AM) perform worst
5. Users seeing **100+ ads convert at 16.91%**
   vs only 0.33% for users seeing 0-10 ads
6. Both groups see similar ad volume (median ~13)
   Higher conversion is due to **better ad content**

---

## ✅ Recommendations
1. Continue and scale the real ad campaign
2. Focus ad spend on **Monday and Tuesday**
3. Schedule ads between **2PM-5PM** for maximum impact
4. Increase ad frequency — more exposure = higher conversion
5. Reduce PSA budget — real ads clearly outperform
6. Invest in better **ad creative content** quality

---

## 📈 Visualizations
1. Conversion Rate — Ad vs PSA (Bar Chart)
2. Conversion Rate by Day of Week (Line Chart)
3. Conversion Rate by Hour (Line Chart)
4. Total Ads Distribution by Group (Box Plot)
5. Conversion by Ad Volume Group (Bar Chart)
6. Statistical Summary Table

---

## 🚀 How to Run
Install required libraries:
pip install pandas numpy matplotlib seaborn scipy statsmodels
Open notebook:
jupyter notebook marketing_ab_test.ipynb

---

## 👤 Author
**Sowmiya Devi**
Aspiring Data Analyst
📧 sowmiyadevi1508@gmail.com
🔗 https://www.linkedin.com/in/sowmiyadevi-da/
