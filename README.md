# 💼 Sales Performance Dashboard (Power BI)

## 🧾 Project Overview
This project presents an **interactive Power BI Sales Dashboard** that provides an analytical view of a company’s **sales, profit, and customer performance** across various regions, categories, and time periods.  
The dashboard helps management monitor **key metrics, identify growth opportunities, and make data-driven business decisions**.

---

## 🎯 Objective
- To visualize and track company-wide sales and profit performance.
- To analyze sales trends across **regions, product categories, and customer segments**.
- To highlight **top-performing products, markets, and sales representatives**.
- To enable interactive exploration of business KPIs through filters and visuals.

---

## 🧮 Dataset Description
The dataset used for this dashboard includes transactional sales and profit data, capturing performance metrics across different dimensions.

| **Column** | **Description** |
|:--|:--|
| `Order ID` | Unique identifier for each sales transaction |
| `Order Date` | Date when the order was placed |
| `Customer ID` | Unique identifier for each customer |
| `Region` | Geographical sales region |
| `Category` | Product category (e.g., Furniture, Technology, Office Supplies) |
| `Sub-Category` | Specific product type |
| `Sales` | Total revenue from the sale |
| `Profit` | Net profit earned |
| `Quantity` | Number of units sold |
| `Discount` | Discount percentage applied |
| `Ship Mode` | Delivery method used for the order |

**Data Source:** Company sales dataset (cleaned and preprocessed)  
**Tool Used:** Microsoft Power BI  

---

## ⚙️ Methodology

1. **Data Preparation**
   - Imported raw data from Excel/CSV into Power BI.
   - Cleaned dataset using **Power Query** (removed duplicates, handled missing values).
   - Created date hierarchy fields (Year, Month, Quarter).
   - Built data model with proper relationships between tables (Sales, Products, Customers, Regions).

2. **Data Analysis**
   - Calculated measures using **DAX (Data Analysis Expressions)** for:
     - Total Sales  
     - Total Profit  
     - Profit Margin %  
     - Sales Growth %  
     - Average Order Value  

3. **Dashboard Development**
   - Created dynamic visuals for key metrics.
   - Added **interactive filters and slicers** (Region, Category, Date).
   - Designed clean and intuitive layout using Power BI design principles.

---

## 📊 Dashboard Components

| **Section** | **Visual Type** | **Description** | **Key Insight** |
|--------------|----------------|-----------------|-----------------|
| **KPI Summary** | Card Visuals | Displays Total Sales, Total Profit, and Profit Margin | Quick snapshot of business performance |
| **Sales by Region** | Map or Column Chart | Compares total sales across geographical regions | Identifies best-performing markets |
| **Profit by Category** | Bar Chart | Shows profit distribution by product category | Reveals which product lines drive profitability |
| **Sales Trend Over Time** | Line Chart | Displays monthly/quarterly sales trend | Tracks growth and seasonality |
| **Top 10 Products by Sales** | Horizontal Bar Chart | Lists products generating the highest revenue | Highlights top-performing SKUs |
| **Sales vs Profit** | Scatter Plot | Correlates revenue with profitability per product or region | Identifies high-revenue but low-margin areas |
| **Customer Segment Analysis** | Donut Chart | Shows share of sales from each customer group | Helps target key customer demographics |

---

## 📈 Key Insights
- **Regional Performance:** Certain regions consistently outperform others in both sales and profit.  
- **Product Insights:** Technology and Furniture categories contribute the most to total revenue.  
- **Customer Trends:** Enterprise customers purchase in bulk and generate higher profit margins.  
- **Seasonal Trends:** Sales peak during Q4, indicating strong holiday demand.  
- **Profit Margins:** Discounts reduce profit margins in specific categories — optimization required.

---

## 💡 Business Recommendations
- Increase marketing and stock availability in **top-performing regions**.  
- Review **discount strategies** to improve profit margins.  
- Focus on **customer retention** for high-value customer segments.  
- Expand **product availability** for high-demand subcategories.  
- Use dashboard insights for **forecasting and performance reviews**.

---

## 🧩 Tools & Technologies Used
- **Power BI** – Dashboard creation and visualization  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – KPI calculations and measures  
- **Excel / CSV** – Data source  
- **Data Modeling** – Relationship building and star schema design  

---

## 🗂️ Project Structure
| File | Description |
|:--|:--|
| `sales dashboard.pbix` | Power BI dashboard file |
| `README.md` | Project documentation (this file) |
| `Dataset.xlsx` *(optional)* | Original dataset (if included) |

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/sales-performance-dashboard.git
2. Open the .pbix file in Power BI Desktop.
3. Click Refresh to load the latest data.
4. Use filters and slicers to explore the dashboard interactively.
5. Customize visuals or measures as needed.

🏁 **Conclusion**

This Power BI Sales Dashboard transforms raw transactional data into clear and actionable insights.
It helps stakeholders visualize business performance across multiple dimensions — enabling smarter, faster, and data-driven decision-making.
