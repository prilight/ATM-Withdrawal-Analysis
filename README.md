# ATM Withdrawal Behavior Analysis

This project explores ATM withdrawal behavior across 35 machines located in four Nigerian states—Kano, Enugu, Lagos, and the Federal Capital Territory (FCT). Using a real-world dataset from Kaggle, I performed data cleaning, merging, exploratory analysis with Python (Pandas, NumPy, Seaborn, Matplotlib), and built an interactive Tableau dashboard to visualize key trends.

## Tools Used
- **Python**: Data cleaning, transformation, EDA
- **Pandas & NumPy**: Merging/joining datasets, calculating KPIs
- **Matplotlib & Seaborn**: Visualizing distributions and trends
- **Tableau**: Dashboard creation for insights storytelling

---

## Project Structure

atm-withdrawal-analysis/
- data/ # Raw and cleaned datasets
- notebooks/ # Jupyter notebooks used for analysis
- dashboard/ # Tableau visualizations (screenshots, .twbx)
- insights/ # Final report, charts
- README.md

---

##  Key Insights

###  Transaction Overview
- **Total transactions:** 1,048,575  
- **Total amount withdrawn:** ₦18,478,995,000  
- **Average transaction amount:** ₦17,623  
- **Median transaction:** ₦10,000  
- **Mode transactions:** ₦50,000 (129,421 times), ₦100,000 (37,514 times)

###  Transaction Amount Distribution
- **Q1:** ₦6,000  
- **Q2 (Median):** ₦10,000  
- **Q3:** ₦20,000  
- **IQR:** ₦14,000  
- **Upper whisker:** ₦30,000  
- **Outliers:** ₦50,000 and ₦100,000 were disproportionately frequent, likely due to withdrawal limits or caps.

---

##  When Do People Withdraw?

- **Peak Hour:** 4 PM – 5 PM  
- **Most Active Period:** 7 AM – 6 PM  
- **Late Night (0–3 AM):** Almost no activity  

###  Monthly Trends:
- **Most Active Month:** January  
- **Least Active Month:** November

###  Day Trends:
- **Weekend Usage (Sat & Sun):** Slightly higher than weekdays  
- **Holiday Transactions:** Surprisingly high (1 million+) over just 8 holidays—suggesting festive rushes or salary events

---

##  Who's Withdrawing?

###  Gender:
- Female: 528,242 transactions  
- Male: 520,333 transactions

###  Top Occupations:
- Health Professionals (Female): 91,038  
- Students: 99,449 (Male & Female combined)  
- Traders, Lawyers, Engineers, Data Analysts also showed strong activity

---

##  Where?

### By State:
- **Kano:** 458,764 transactions (10 ATMs)  
- **Enugu:** 350,251 transactions (9 ATMs)  
- **FCT:** 159,652 transactions (6 ATMs)  
- **Lagos:** 79,908 transactions (15 ATMs — all underperforming)

### Underperforming ATMs:
- **17 ATMs flagged** as underperforming (below average of 26,214 transactions/year)
- Lagos machines averaged just **5,000–6,000 transactions**
- Notably low performers in FCT: Lugbe and Garki ATMs

---

##  Recommendations

- **Reassess ATM placement in Lagos:** Is access harder or demand genuinely lower?
- **Expand availability during peak hours (4–5 PM)** to reduce queue pressure
- **Redistribute or promote underused ATMs** to more strategic locations
- **Leverage customer segmentation** (e.g. students, professionals) for targeted service delivery

---

## 📌 Next Steps
- Explore transaction *success/failure* if data becomes available
- Add clustering models for customer segmentation
- Incorporate real-time withdrawal predictions (if timestamp granularity improves)

---

##  Dashboard Preview
See the `/dashboard/` folder for a screenshot and link to the interactive Tableau dashboard.

---

##  Contact
Feel free to connect on [LinkedIn](www.linkedin.com/in/precious-joshua-omoladun) or drop feedback!

---

**#DataAnalytics #Python #Tableau #Kaggle #ATMAnalysis #EDA #RealWorldData #BankingAnalytics**
