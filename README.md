# sql-ecommerce-cleaning-project
MySQL project to clean and normalize messy e-commerce sales data

# 🛍️ E-commerce Data Cleaning & Normalization (MySQL)

This project showcases how I cleaned and normalized a messy e-commerce sales dataset using **MySQL Workbench**. The goal was to prepare the data for accurate analysis by ensuring consistency, removing errors, and applying normalization best practices.

---

## ✅ Key Data Cleaning Tasks

- Removed unnecessary symbols, numbers, and special characters from text and phone numbers  
- Created a `bad phone no.` column to identify invalid numbers  
- Standardized phone numbers by adding "1" to 10-digit entries  
- Rounded unit prices and total amounts to two decimal places  
- Corrected date formatting issues, including dates written with text  
- Identified and flagged outliers using ±3 standard deviations  
- Removed duplicate records using `DISTINCT` and proper keys  
- Added new primary keys for uniqueness and dropped duplicate IDs

---

## 🔄 Data Normalization

- Set up parent-child relationships between tables  
- Created foreign key and primary key constraints  
- Structured tables like transactions, customers, products, sales reps, and stores  
- Rebuilt relationships to support clean querying and analysis

---

## 🧰 Tools Used

- MySQL Workbench  
- SQL  
- WordPress (for documentation)

---

## 📸 Project Documentation (with Screenshots)

📖 Full write-up and images showing each cleaning step:  
👉 [View on WordPress](https://josephifechukwu.wordpress.com/e-commerce-sales-data-cleaning-and-normalization-project/)

---

## 👤 Author

**Joseph Ifechukwu**  
🎓 Mass Communication Student | 📊 Aspiring Data Analyst | 🛒 E-commerce Enthusiast  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/your-profile) <!-- Replace with your actual LinkedIn URL -->

