# 🎥 Movie Revenue Analysis with Pivot Tables  

## 📊 Objective  
Analyze movie data to understand:  
- **Total revenue generated each year**  
- **Average revenue per movie**  
- **Revenue trends over time**  

---

## 🔎 Analysis Steps  

### 1. Total Revenue Per Year  
We started by creating a pivot table to show **Box Office Revenue** grouped by **Year**. This gave us a clear view of overall earnings across the dataset.  

- **Key Insight:** 2014 had the highest total revenue, while 2016 had the lowest.  
- **Important Note:** This alone can be misleading as the number of movies released each year varies significantly.  

### 2. Average Revenue Per Movie  
To gain a more accurate perspective, we added a second column to the pivot table to calculate the **Average Revenue per Movie** for each year.  

- **Key Insight:** Despite the high total revenue in 2015, its average revenue per movie was significantly lower than in other years.  

### 3. Deep Dive into 2015  
Given the unusually low average revenue per movie in 2015, we dug deeper to identify potential causes.  

- **Finding:** 2015 had the **highest number of movies released** in the dataset.  
- This volume likely included many lower-grossing films, which pulled the overall average down despite strong total revenue.  

### 4. Low Revenue Outliers in 2015  
To confirm this hypothesis, we filtered for movies with revenue under **$10M** in 2015.  

- **Result:** Out of 124 movies released, **20 (16.13%)** earned less than **$10M**.  
- **Comparison:** This is significantly higher than other years, where the proportion of sub-$10M movies averaged around **10%**.  

![image](https://github.com/user-attachments/assets/edce7783-5b6c-4484-a12a-3d07581bd87c)


---

### 5. 📉 Conclusion  
This analysis suggests that a **higher proportion of low-grossing films** significantly impacted the overall average revenue per movie in 2015, despite strong total earnings.  

---

📝 **Next Steps:**  
Consider exploring other factors like genre, production budgets, and marketing impact to further refine this analysis.  

### 6. 📉 Analysing AVG profit by genge

![image](https://github.com/user-attachments/assets/2b84571a-81d4-4579-bb21-14931e399a2e)
Analyzing the average profit by genre, we can notice that the action genre has a significant advantage over the others.







