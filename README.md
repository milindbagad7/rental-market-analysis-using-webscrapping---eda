# 🏠 Rental Market Analysis Using Web Scraping & Exploratory Data Analysis (EDA)

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Objective](#-business-objective)
- [Tools & Technologies](#-tools--technologies)
- [Web Scraping Process](#-web-scraping-process)
- [Data Preparation](#-data-preparation)
- [Before Data Cleaning](#before-data-cleaning)
- [After Data Cleaning](#after-data-cleaning)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Visuals](#-key-visuals)
- [Key Insights](#-key-insights)
- [Experience & Challenges](#-experience--challenges)
- [Conclusion & Learnings](#-conclusion--learnings)
- [Author & Contact](#-author--contact)

---

## 📌 Overview
This project focuses on analyzing the residential rental market by **scraping real-time property data** from online real-estate platforms and applying **Exploratory Data Analysis (EDA)** to identify rental pricing trends.

Since no clean public dataset was available, the dataset was **created from scratch using web scraping**, followed by extensive data cleaning, transformation, and analysis.  
The project compares **Pune and Nashik rental markets** to highlight pricing differences, demand patterns, and influencing factors.

---

## 🎯 Business Objective
- Build a **structured rental dataset** using web scraping  
- Clean and preprocess **raw, unstructured property data**  
- Analyze **rental price patterns** using EDA  
- Identify **key factors affecting rent**  
- Deliver **actionable insights** for tenants, owners, and real-estate stakeholders  

---

## 🛠️ Tools & Technologies
- **Python**
- **BeautifulSoup**
- **Requests**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🌐 Web Scraping Process
1. Imported required libraries (`BeautifulSoup`, `Requests`)
2. Selected a real-estate listing website
3. Extracted property-level details such as:
   - Rent
   - BHK type
   - Carpet area
   - Furnishing status
   - Floor details
   - City and locality
4. Stored the extracted data in a **Pandas DataFrame**

---

## 🧹 Data Preparation
- Removed currency symbols, commas, and text units
- Converted text columns into numeric and categorical variables
- Handled missing and inconsistent values
- Standardized formats and units
- Parsed multiple attributes from single HTML tags using **regex**

---

## Before Data Cleaning
<img width="1189" height="255" alt="Before Data Cleaning" src="https://github.com/user-attachments/assets/610bcbfc-9c89-48bd-84fb-20429379380f" />

---

## After Data Cleaning
<img width="1189" height="255" alt="After Data Cleaning" src="https://github.com/user-attachments/assets/4ad523c0-dee4-4cdf-b956-e97d78f2ea54" />

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analysis Performed
- BHK-wise distribution analysis
- Furnishing status distribution
- Rent distribution trends
- Average rent by **BHK and furnishing**
- Carpet area vs rent relationship
- **City-wise comparison** between Pune and Nashik

---

## 📈 Key Visuals
<img width="856" height="679" alt="EDA Visual 1" src="https://github.com/user-attachments/assets/afd034bf-6c39-41b5-afc8-39fda5a6fea2" />

<img width="896" height="728" alt="EDA Visual 2" src="https://github.com/user-attachments/assets/a61b5827-1674-47e5-ac22-cd6b4c5a8bc6" />

<img width="717" height="616" alt="EDA Visual 3" src="https://github.com/user-attachments/assets/c59b83e8-33e4-4809-b091-17f942c51f36" />

---

## 🔍 Key Insights
- **2 BHK and 3 BHK** flats are the most commonly available
- Most rental properties fall in the **₹15,000 – ₹40,000** range
- Rent increases **non-linearly** as BHK size increases
- **Furnished flats** consistently command higher rent
- Strong positive correlation between **carpet area and rent**
- **Pune is significantly more expensive than Nashik**
- Nashik offers stable and budget-friendly rental pricing

---

## 🚧 Experience & Challenges
- Built a dataset from scratch due to lack of public data
- Worked with highly unstructured website content
- Performed extensive text cleaning and regex parsing
- Managed missing values and inconsistent formats

---

## ✅ Conclusion & Learnings
- Successfully developed a **clean, structured rental dataset**
- Identified **BHK, carpet area, furnishing, city, and locality** as major rent drivers
- Discovered strong rental trends and city-wise differences
- Demonstrated end-to-end skills in **web scraping, data cleaning, EDA, and insight generation**

---

## 👤 Author & Contact
**Milind Suresh Bagad**  
🎓 Bachelor of Computer Applications (BCA)  
📊 Aspiring Data Analyst / Data Scientist  

🔗 **LinkedIn:** https://www.linkedin.com/in/milind-bagad-82786a224  
🔗 **GitHub:** https://github.com/milindbagad7
---

⭐ If you find this project useful, consider giving it a star!
