# 🏠 Rental Market Analysis Using Web Scraping & Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on analyzing the residential rental market by **scraping real-time property data** from online real-estate platforms and performing **Exploratory Data Analysis (EDA)** to uncover key rental pricing patterns.

Since no clean public dataset was available, the entire dataset was **built from scratch using web scraping**, followed by data cleaning, transformation, and analysis.  
The study mainly compares **Pune and Nashik rental markets** to highlight pricing differences, demand patterns, and influencing factors.

---

## 🎯 Objectives of the Project
- Build a **structured rental dataset** using web scraping
- Clean and preprocess **raw, unstructured property data**
- Analyze **rental price patterns** using EDA
- Identify **key factors influencing rent**
- Generate **actionable insights** for tenants, owners, and real-estate stakeholders

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
2. Selected a target real-estate website
3. Extracted property-level information such as:
   - Rent
   - BHK type
   - Carpet area
   - Furnishing status
   - Floor details
   - City & locality
4. Stored scraped data into a **Pandas DataFrame** for analysis

---

## 🧹 Data Cleaning & Preprocessing
- Removed symbols (₹, commas, sqft text, etc.)
- Converted text-based columns into numeric and categorical features
- Handled missing and inconsistent values
- Standardized units and formats
- Parsed multiple features from single HTML tags using **regex**

---
## Before Data Cleanign 

<img width="1189" height="255" alt="image" src="https://github.com/user-attachments/assets/610bcbfc-9c89-48bd-84fb-20429379380f" />


---

## After  Data Cleanign 
<img width="1189" height="255" alt="image" src="https://github.com/user-attachments/assets/4ad523c0-dee4-4cdf-b956-e97d78f2ea54" />

---

## 📊 Exploratory Data Analysis (EDA)

### Key Analysis Performed
- Distribution of **BHK types**
- Furnishing status distribution
- Rent distribution analysis
- Average rent by **BHK & furnishing**
- Carpet area vs rent correlation
- **City-wise comparison** (Pune vs Nashik)

---
# Key Visuals
<img width="856" height="679" alt="image" src="https://github.com/user-attachments/assets/afd034bf-6c39-41b5-afc8-39fda5a6fea2" />
<img width="896" height="728" alt="image" src="https://github.com/user-attachments/assets/a61b5827-1674-47e5-ac22-cd6b4c5a8bc6" />
<img width="717" height="616" alt="image" src="https://github.com/user-attachments/assets/c59b83e8-33e4-4809-b091-17f942c51f36" />


---

## 🔍 Key Insights
- **2 BHK and 3 BHK** flats are the most commonly available rental options
- Majority of rents fall in the **₹15,000 – ₹40,000** range
- Rent increases **exponentially** with BHK size
- **Furnished flats** consistently charge higher rent than semi-furnished and unfurnished
- **Carpet area has a strong positive correlation** with rent
- **Pune is significantly more expensive than Nashik** across all BHK types
- Nashik shows stable and affordable pricing, while Pune reflects a premium and luxury market

---

## 🚧 Challenges Faced
- No ready-made dataset available
- Mixed and unstructured text data on websites
- Required extensive cleaning, regex parsing, and feature engineering
- Handling missing values and inconsistent formats

---

## ✅ Conclusion
- Successfully built a **clean, structured rental dataset** from raw web data
- Identified **BHK, carpet area, furnishing, city, and locality** as major rent drivers
- Discovered clear rental trends and city-wise pricing differences
- The analysis provides **data-driven insights** useful for tenants, owners, and real-estate professionals

---

## 👤 About Me
**Milind Suresh Bagad**  
🎓 Bachelor of Computer Applications (BCA)  
📊 Aspiring Data Analyst / Data Scientist  
💡 Interested in data-driven problem solving and real-world analytics projects

🔗 **LinkedIn:** https://www.linkedin.com/in/milind-bagad-82786a224  
🔗 **GitHub:** https://github.com/Milind5  

---

## ⭐ If you find this project useful, consider giving it a star!
