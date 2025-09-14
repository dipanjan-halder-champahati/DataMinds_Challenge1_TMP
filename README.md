# DataMinds_Challenge1_TMP

📊 **The EDA Mission Briefing**  
This repository contains our team's submission for **The Manhattan Project's Exploratory Data Analysis (EDA) Group Challenge**.  
Our mission was to analyze the provided dataset to uncover **actionable insights for OmniMart Retailers**, focusing on **customer behavior, product performance, and operational efficiency**.

---

## 👥 Team: DataMinds
- **Dipanjan Halder** – Lead Analyst & Documentation  
- **Ekadashi Sardar** – Visualization Specialist  
- **Anshika Pandey** – Data Cleaning & Preprocessing  
- **Nilanjana Saren** – Report & Presentation Editing  

---

## 🚀 How to Run This Project
1. Open **Google Colab**  
2. Upload the `analysis.ipynb` notebook  
3. Run all cells step by step to reproduce the analysis  

---

## 🔍 Key Insights & Findings

### 📊 Executive Summary
- Typical transaction: ~5 items, median item price ≈ ₹255  
- Median basket value: ≈ ₹1,041, but a small % of orders reach ≈ ₹4,999 → high-value outliers exist  
- Customer base: Average age ≈ 35.7 years  
- Customer ratings: Average rating ≈ 3.18 (room for improvement)  
- Temporal patterns: Sales fluctuate significantly by month/quarter  

---

### 🧾 Key Findings (Evidence from Analysis)
- **Basket size & price**: Median Total_Purchases = 5; Median Amount = 255  
- **Revenue**: Mean Total_Amount = 1,367; Total Revenue ≈ 407M; Max ≈ 4,999  
- **Ratings**: Mean = 3.18; very weak correlation with spend  
- **Age**: Average = 35.7; little correlation with purchases  
- **Outliers**: High-value transactions exist (IQR outliers in Total_Amount)  
- **Top categories/brands**: A small group contributes most of revenue (pie/donut/bar plots confirm concentration)  

---

### ✅ Actionable Recommendations
1. **Increase Average Order Value (AOV)**  
   - Bundle offers (e.g., *buy 4 get 1 discounted*)  
   - Free shipping thresholds slightly above median basket value (~1,400–1,500)  
   - *Evidence*: Basket median = 5 items, item median price = 255  

2. **Nurture High-Value Customers**  
   - Identify outlier transactions (orders > 4,000)  
   - Build VIP segment with exclusive offers & loyalty programs  
   - *Evidence*: Max Total_Amount ≈ 4,999; right-skewed revenue distribution  

3. **Improve Ratings & Customer Experience**  
   - Focus on categories/brands with lowest ratings  
   - Fix product pages, delivery messaging, after-sales support  
   - *Evidence*: Average rating = 3.18; variation across categories/brands in boxplots  

4. **Demographic Targeting**  
   - Main age group = 25–40 years → tailor offers & ads for this segment  
   - Track behavior differences in <25 and 40+ age groups  
   - *Evidence*: Mean age ≈ 35.7; crosstab Category × Age_Group confirms segmentation  

5. **Merchandising Focus**  
   - Promote top 10 categories/brands via homepage highlights & cross-sell  
   - Reassess low-performing categories → promos or consolidation  
   - *Evidence*: Revenue distribution plots (pie/donut)  

6. **Time-Based Promotions**  
   - Use monthly/quarterly sales trends to optimize campaigns & inventory  
   - Push marketing in slow months, maximize during peaks  
   - *Evidence*: Monthly and quarterly revenue plots  

➡️ For a more detailed breakdown, please refer to the full **analysis.ipynb** notebook and the **presentation.pdf** file.  

---

## 📁 Repository Structure
- `README.md` → This documentation file  
- `retail_data.zip` → Dataset used for the challenge  
- `analysis.ipynb` → Jupyter/Colab notebook with all analysis  
- `presentation.pdf` → Final presentation slides summarizing insights & recommendations  

---

## 🛠️ Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Google Colab / Jupyter Notebook**  
- **GitHub** for version control and collaboration  

---

✨ *Team DataMinds – Turning Data into Decisions!*  
