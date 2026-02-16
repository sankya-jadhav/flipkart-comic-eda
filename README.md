# 📊 Flipkart Comic Market Analysis (EDA Project)

## 🔎 Project Overview
This project performs an end-to-end Exploratory Data Analysis (EDA) on comic and manga listings from Flipkart to identify **value-for-money options** for students and beginner readers.

The analysis compares comics from **India, Japan, and the United States** based on price, discounts, ratings, reviews, formats, and publishers to determine the best choices for affordability and quality.

---

## 🎯 Problem Statement
As a student with limited budget, choosing the right comic or manga can be difficult.  
This project answers:

- Which country offers the most affordable comics?
- Do higher discounts mean lower quality?
- Which publishers provide the best reader satisfaction?
- Which format (Paperback, Hardcover, Box Set) gives the best value?

---

## 🔄 Project Workflow

### 1️⃣ Web Scraping
- Extracted comic data from Flipkart
- Parsed HTML using **BeautifulSoup**
- Cleaned values using **Regex**

### 2️⃣ Data Cleaning
- Handled missing values
- Standardized price, discount, and rating formats
- Structured dataset using **Pandas**

### 3️⃣ Exploratory Data Analysis
- Price distribution
- Discount vs price comparison
- Country-wise analysis (India, Japan, US)
- Publisher and format insights
- Reader engagement using review counts

### 4️⃣ Business Insights
- Identified best value-for-money comics
- Recommended beginner-friendly formats & publishers

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- Matplotlib & Seaborn
- BeautifulSoup
- Regular Expressions (Regex)
- Jupyter Notebook

---

## 📂 Project Structure

```
flipkart-comic-eda/
│
├── 01_Web_Scraping.ipynb # Data collection from Flipkart
├── 02_EDA_Comic.ipynb # Data analysis & visualization
├── Comicbooks.csv # Clean dataset
├── Presentation.pptx # Project presentation
└── README.md
```


---

## 📊 Key Insights

### 🌍 Country Comparison
- **Japan** → Highest ratings & reader engagement
- **India** → Most affordable & budget-friendly
- **United States** → Highest prices but low engagement on Flipkart

### 💸 Pricing & Discounts
- Majority of comics priced under ₹5000
- Japan offers higher discounts
- India provides best affordability + moderate discounts

### ⭐ Reader Satisfaction
- Japanese and ACK publishers → Highest ratings (4.1★–4.3★)
- Marvel & DC → Lower ratings on Flipkart despite global popularity

### 📚 Format Analysis
- **Paperback** → Most affordable & beginner-friendly
- Hardcover → Expensive, not ideal for students
- Box sets → Premium bundles

---

## 🏆 Final Recommendation
For beginners and students:

✅ Choose **Japanese Manga** for quality & engagement  
✅ Choose **Indian (ACK)** comics for affordability  
✅ Prefer **Paperback format** for best value  

---

## 📈 Business Value
This analysis demonstrates how data can support:
- Smart purchasing decisions
- Market comparison
- Customer preference analysis
- Budget optimization for students

---

## 👤 Author
**Sanket Jadhav**  
🎓 BCA Graduate | Aspiring Data Analyst  
🔗 LinkedIn: [Sanket Jadhav](https://www.linkedin.com/in/sanketjadhav02/)  
🔗 GitHub: https://github.com/sankya-jadhav

---

## 🚀 Future Improvements
- Add interactive dashboard (Power BI / Tableau)
- Expand dataset from multiple e-commerce platforms
- Perform price prediction using machine learning


