# 🛍️ E-Commerce Data Analysis & Visualization with Python

This project was completed as part of the **Careerha Data Analysis Scholarship** program, where I applied the skills learned in Python and Excel to perform end-to-end analysis on real e-commerce datasets.

It includes data cleaning, merging, exploratory analysis, and data visualization to extract insights and support data-driven decisions.

---

## 📦 Datasets Used

- `Products.xlsx` – product details
- `Customer Data.xlsx` – customer information
- Multiple sales files (`.csv`) – sales transactions

---

## 🧹 Data Processing Steps

1. **Data Importing**  
   Loaded Excel and CSV files using `pandas`.

2. **Data Cleaning**
   - Converted data types (e.g. dates, IDs, prices).
   - Removed null rows.
   - Standardized country names.
   - Applied custom functions to split complex fields.

3. **Data Merging**
   - Joined `sales`, `products`, and `customers` into a single dataset.
   - Filled missing values with `'N/A'`.

---

## 📊 Analysis Performed

- **Total Sales by Year** (line chart)
- **Sales by Month** (seasonal trends)
- **Orders by Ship Mode** (with % distribution)
- **Sales by Product Category** and **Sub-Category**
- **Customer Distribution by Segment**
- **Sales by Country**
- **Top 10 Products by Sales**

---

## 💡 Key Insights

- 2014 had the highest total sales; 2017 the lowest.
- September was the top sales month; February was the lowest.
- “Standard Class” dominated shipping (59% of orders).
- Technology is the top-performing product category (40% of total sales).
- The majority of customers belong to the “Consumer” segment (51%).
- USA is the main market, followed by Egypt.

---

## ✅ Recommendations

- Focus marketing efforts during high-performing months (e.g. September).
- Improve campaigns in low-performing months like February.
- Promote top-selling products with bundles and upselling.
- Target “Corporate” and “Home Office” segments with tailored offers.
- Fix missing country and customer segment data to improve accuracy.

---

## 📌 Technologies Used

- Python 3 (Pandas, Matplotlib, Calendar, OS)
- Jupyter Notebook / Google Colab
- Excel for raw data storage and inspection
- PowerPoint for result presentation

---

## 📁 Project Structure


/data
└── products.xlsx
└── customer_data.xlsx
└── sales/ (CSV files)

/figures
└── sales_by_year.png
└── top_products.png


---

## 🙋‍♀️ Author

**Rahma Mohamed Hashem**  
Data Analysis & Visualization | Excel | Python | E-Commerce

