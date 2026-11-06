# Databel Customer Churn Analysis Dashboard

An end-to-end data analytics project analyzing customer attrition for Databel, a telecom provider. This dashboard provides key insights into overall churn rates, primary churn reasons, customer demographics, contract behaviors, and customer service performance.

---

## 📊 Dashboard Overview

[Databel Dashboard.pdf](https://github.com/user-attachments/files/34500332/Databel.Dashboard.pdf)


---

## 📊 Key Metrics Summary

- **Total Customers:** ~7,000 (7K)
- **Churned Customers:** ~2,000 (2K)
- **Overall Churn Rate:** 27%
- **Total Charges Generated:** $7 Million
- **Average Monthly Charge:** $31

---

## 🔍 Key Insights & Visualizations

### 1. Primary Drivers & Categories of Churn
- **Top Reason:** *Competitor made better offer* (303 customers), followed by *Competitor had better devices* (297 customers) and *Attitude of support person* (203 customers).
- **Churn Categories:** Competitors account for the largest proportion of churn (805 customers), followed by Support/Attitude issues (287 customers), Dissatisfaction (286 customers), and Pricing (200 customers).

### 2. Customer Service Call Thresholds
- Customer churn remains low for **0 to 2 customer service calls** ($9\% - 37\%$).
- Churn skyrockets to **88% at 3 calls** and reaches **100% at 4+ calls**.
- **Takeaway:** Customers calling customer support 3 or more times are at critical risk of leaving.

### 3. Contract Types & Pricing Impact
- **Monthly Contracts:** Highest churn rate (~40%–47% across genders).
- **Yearly Contracts:** Significantly lower churn (~6%–7%).
- **Group/Family Plans:** Customers in group plans pay a lower average monthly charge ($23 vs. $33) and demonstrate significantly lower churn rates.

### 4. Age & Geographic Distribution
- **Age Impact:** Churn rates increase significantly among older age brackets, spiking to over **50%–60%** for customers aged 70 to 85.
- **Geographic Coverage:** Visualized on an interactive Azure map to identify regional churn clusters across North America.

---

## 🛠️ Dashboard Features & Slicers

The dashboard includes global interactive filters to dynamic slice data across:
- **State / Region**
- **Gender** (Female, Male, Prefer not to say)
- **Group Discount Status** (Yes / No)
- **Payment Method**


---

## 🚀 Recommended Actions

1. **Competitor Retention Strategies:** Create competitive targeted offers and hardware upgrade incentives to combat competitor poaching.
2. **Support Escalation Protocols:** Flag accounts automatically when customer support call volume reaches **2 calls** to resolve issues before the 3-call threshold.
3. **Incentivize Annual Contracts & Group Plans:** Offer promotional discounts to transition monthly subscribers to 1-year/2-year plans and promote family/group packages.
4. **Senior Customer Support:** Develop tailored onboarding and tech support for older demographic segments ($\ge 65$ years old).
