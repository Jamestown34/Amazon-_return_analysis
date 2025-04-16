# 📦 Returns Analysis: Reducing Product Returns with Data

## 📍 Overview

In the competitive world of e-commerce, product returns can be a major challenge — costing businesses both time and money. This project explores the patterns behind product returns, identifies common reasons, and provides actionable recommendations to help reduce return rates. The analysis was conducted using a structured dataset of fashion product returns.

The main goal was to identify which products are most often returned and understand why, so that smarter business decisions can be made to improve customer satisfaction and profitability.

---

## 🎯 Objectives

- Clean and transform raw product return data
- Extract and standardize product information (such as SKU and size)
- Categorize return reasons for better insight
- Visualize trends through summary statistics and Pivot Tables
- Offer recommendations to help reduce product returns

---
<img src="https://github.com/Jamestown34/Amazon-_return_analysis/blob/main/return_photos/Screenshot%20(75).png" width="600"/>



## 🧰 Tools & Technologies Used

- **Python** – for data cleaning and feature extraction  
- **Pandas** – for data manipulation  
- **Regex** – to extract product codes and sizes from SKU fields  
- **Excel** – for visualizing insights using Pivot Tables  
- **XlsxWriter** – for creating automated Excel reports

---

## 📊 Dataset Summary

The dataset contains detailed records of returned fashion items, including:

- Return date  
- SKU (Stock Keeping Unit)  
- Quantity returned  
- Product gender  
- Return reason  
- Return status  

One major challenge was dealing with inconsistent SKU formatting, which required cleaning and parsing to separate the product code from the size.

---

## 🧹 Data Cleaning & Transformation

The raw dataset contained SKUs in messy, inconsistent formats like "161_FBA_M/38" and "124/s/XS". To make the data usable, regular expressions were used to extract two important features:

- **Product Code** – to identify the core item
- **Size** – to detect sizing issues that lead to returns

In addition, null values were handled, columns were renamed for clarity, and return reasons were cleaned for consistency.

---
<img src="https://github.com/Jamestown34/Amazon-_return_analysis/blob/main/return_photos/Screenshot%20(70).png" width="600"/>



## 🧠 Return Reason Categorization

To better understand the reasons customers return products, return reason codes were mapped into broader, human-readable categories:

- **Sizing Issue** – e.g. “too small” or “too large”  
- **Damaged** – item arrived damaged  
- **Listing Issue** – not as described, missing parts, etc.  
- **Other/Unknown** – miscellaneous reasons or missing data

This helped reveal key insights about product performance and areas needing attention.

---

## 📈 Insights & Key Findings

- Certain SKUs had significantly higher return rates due to sizing issues, suggesting poor size accuracy or misleading product info
- Several products were frequently returned as “not as described”, pointing to possible listing quality problems
- Larger sizes (e.g., XL, XXL) had higher return frequencies, highlighting a need to review fit or size chart accuracy
- Products tagged as “FBA” or containing special size codes showed inconsistent formatting, which may affect tracking and reporting

---

## 📊 Deliverables

- A cleaned and enriched dataset with new columns: Product Code, Size, and Return Category  
- An Excel report featuring:
  - Return frequency by SKU
  - Returns by size
  - Return reason distribution
- Business recommendations to reduce returns

---

## 💼 Business Recommendations

Based on the analysis, the following actions are recommended:

- **Pause or review high-return SKUs**: Items with frequent sizing or description issues should be evaluated or temporarily removed
- **Improve product listings**: Ensure size charts, product descriptions, and images are accurate and comprehensive
- **Track returns by size and gender**: Identify patterns that might affect different customer segments
- **Standardize SKU format**: Clean SKU formatting for better tracking and easier reporting

---

## 🚀 Next Steps

- Integrate feedback data with inventory systems for real-time monitoring  
- Develop a predictive model to flag high-return-risk products  
- Build an interactive dashboard using tools like Power BI or Tableau  
- Conduct customer sentiment analysis on return reasons (if textual feedback is available)

---

## 🙌 Conclusion

This project showcases the value of combining data cleaning, transformation, and simple analytics to solve a real-world retail problem. By understanding the "why" behind product returns, businesses can make data-informed decisions to enhance the shopping experience and reduce operational waste.

It’s a strong example of how even basic data analysis — when done right — can uncover meaningful insights and drive measurable improvements.

---

**Thanks for reading!** If you're interested in collaborating or have feedback, feel free to connect. 🚀
