# 🏫 Exploring NYC Public School Test Result Scores  
---

Every year, American high school students take the **SATs**, standardized tests that measure literacy, numeracy, and writing skills.  
There are three sections:  

- **Reading** (max 800)  
- **Math** (max 800)  
- **Writing** (max 800)  

These scores play a pivotal role in college admissions, making SAT performance an important benchmark for schools, policymakers, researchers, and parents.  

This project analyzes SAT results across New York City (NYC) public schools using **Python & Pandas**.  

---

## 📌 Key Questions  

1. **Which NYC schools have the best math results?**  
   - Criteria: average math score ≥ 640 (≥ 80% of max).  
   - Saved as `best_math_schools`.  

2. **What are the top 10 performing schools based on total SAT score?**  
   - `total_SAT = average_math + average_reading + average_writing`.  
   - Saved as `top_10_schools`.  

3. **Which borough has the largest variation in SAT scores?**  
   - Aggregated by borough.  
   - Results include:  
     - `num_schools`  
     - `average_SAT`  
     - `std_SAT` (standard deviation).  
   - Saved as `largest_std_dev`.  

---

## 📊 Methods  

- Data loaded from `schools.csv`.  
- Used **Pandas** for cleaning, filtering, grouping, and aggregations.  
- Created new column `total_SAT` for combined scores.  
- Grouped by borough to calculate SAT variation.  

---

## ✅ Results  

- **Best Math Schools:** Schools with average math ≥ 640.  
- **Top 10 Schools:** Highest combined SAT scores across NYC.  
- **Most Variable Borough:** The borough with the largest SAT performance spread.  

---


