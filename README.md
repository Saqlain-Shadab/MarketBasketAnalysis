<div align="center">

## 🧺 Market Basket Analysis


</div>


**📌 Project Overview**  
This project is Association Analysis with **Apriori algorithm** to identify frequent itemsets and generate **association rules** from transaction data. The goal is to help businesses understand customer buying habits and optimize product placement, bundling, and cross-selling strategies.

---
**🎯 Objectives**

- Preprocess transaction data into the required format for Apriori  
- Generate frequent itemsets using **support thresholds**  
- Extract association rules using **confidence** and **lift** metrics  
- Visualize strong associations for business insights  

---

**🛠️ Methodology**

**1️⃣ Data Preprocessing**  
- Convert transactional data into a one-hot encoded format  
- Filter out low-frequency items to reduce noise  

**2️⃣ Apriori Algorithm**  
- Generate frequent itemsets using a minimum support threshold  
- Build association rules from itemsets that meet:  
  - **Minimum Confidence** (e.g., ≥ 0.6)  
  - **Minimum Lift** (e.g., ≥ 1.2)

**3️⃣ Rule Evaluation**  
- **Support**: Frequency of itemset in transactions  
- **Confidence**: Likelihood that the consequent is purchased when antecedent is  
- **Lift**: How much more likely the consequent is, given the antecedent  




<!-- Add sample rules or visual output below as needed
These are the references were helpful while completing my project,
https://www.youtube.com/watch?v=4QIWJVVWJdQ&t=771s, https://code.cubewise.com/blog/how-to-run-a-market-basket-analysis-with-tm1py-and-paw -->
