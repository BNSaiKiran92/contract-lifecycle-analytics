# contract-lifecycle-analytics

# Contract Lifecycle Analytics Project

### 🎯 Objective
To identify approval delays, compliance risks, and process inefficiencies in a Contract Lifecycle Management (CLM) system and provide data-driven recommendations for improvement.

---

### 🧩 Dataset
Simulated dataset of **~20,000 contracts (sample of 500 shown)** containing attributes like:
- Contract_Type (SOW, MSA, NDA, Vendor, Employment)
- Department (Tax, Consulting, Audit, HR, Procurement)
- Contract_Value, Term_Days, Clauses_Missing, Amendments_Count
- Approval_Time_Days, Status, Compliance_Flag

---

### ⚙️ Tools Used
**SQL**, **Python (Pandas, NumPy, SciPy)**, **Matplotlib**, **Seaborn**, **Tableau**

---

### 🔍 Methodology
1. **Data Extraction:** SQL queries to fetch contract data from multiple CLM system tables (simulated in this dataset).  
2. **Data Preprocessing:** Cleaned and standardized department names, missing dates, and clause fields.  
3. **Exploratory Data Analysis:** Trend analysis on approval times, contract values, and rejection patterns.  
4. **Statistical Analysis:**  
   - *t-test:* Standard vs Non-standard contract approval times  
   - *Chi-square:* Clause presence vs rejection probability  
   - *ANOVA:* Cycle time variation across departments  
5. **Visualization:** Cycle time distribution, rejection trends, department performance.  

---

### 📈 Key Insights
- **Non-standard contracts** take ~35% longer (avg. 18 vs 12 days).  
- **Missing clauses** increase rejection probability by ~20%.  
- **Departments** show significant variance (p < 0.05) in approval cycle times.  

---

### 💡 Recommendations
- Expand **standard contract templates** to reduce cycle times.  
- Implement **automated clause validation** in draft stage.  
- Target **department-level training** for efficiency improvement.  

---

### 🏁 Outcome
Potential to save **~100,000 days annually** across 20K contracts through faster approvals and reduced rework.

---

### 📊 Visuals
<p align="center">
  <img src="visuals/approval_cycle_trends.png" width="400">
  <img src="visuals/clause_compliance_analysis.png" width="400">
</p>

---

### 👤 Author
**B N Sai Kiran**  
Senior Business Analyst | Data Analytics | SQL | Python | EDA | Hypothesis Testing
