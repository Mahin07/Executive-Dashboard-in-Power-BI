# 🍕 Pizza Sales BI Dashboard — Power BI Portfolio Project

Hi! I'm a Business Intelligence enthusiast, and this is one of my showcase projects where I dive deep into pizza sales data to uncover actionable insights using Power BI. This project demonstrates my ability to clean data, model relationships, write DAX measures, and design executive-level dashboards that drive decision-making.

## 🚀 Project Summary

This dashboard provides actionable insights into pizza sales performance across time, category, and size. It's designed for restaurant managers or executives to:

- Identify high-performing pizza types and sizes
- Understand daily and monthly sales trends
- Optimize inventory and staffing for peak times
- Spot growth opportunities using real data

## 📌 Key Highlights from the Dashboard

- **Slicer-Driven Interactive Reports** for real-time filtering and comparisons.
- **Dynamic Time Series Analysis** to uncover seasonal and daily patterns.
- **Product Category & Size Breakdown** for inventory and menu optimization.
- **Executive KPI Cards** for quick top-level insights.
- 
- 💰 **Total Revenue**
- 🧾 **Average Order Value**
- 🍕 **Total Pizzas Sold** 
- 📦 **Total Orders**
- 📊 **Avg. Pizzas Per Order**

![image](https://github.com/user-attachments/assets/bb487269-ba48-49e2-9ddf-a610a5950ee4)

### 🔥 Busiest Days & Times
- Peak days: **Thursday, Friday, Saturday**
- Peak months: **June** and **January**
- Summer drives more orders; **Winter** boosts revenue

### 🥇 Best Performers
- **Category**: _Classic_ pizzas lead in both revenue and order volume
- **Size**: _Large_ pizzas account for ~46% of all sales

## 💡 Skills Demonstrated

- Power BI Desktop for full report creation
- Power Query for transforming raw data
- DAX for custom KPIs, averages, and trends
- Drill-through, slicers, and bookmarks for interactivity
- UI/UX principles for executive-ready dashboards

![image](https://github.com/user-attachments/assets/7ef035dd-4e38-4edb-ad99-19e3d0ebd54f)

## 🧠 Why This Project Stands Out

- 🎯 Built with stakeholder needs in mind — focused, KPI-driven visuals
- 📚 Clear annotations and data storytelling on the left panel
- 🛠️ Follows best practices in BI development (star schema, clean layout, custom measures)


## ✨ What’s Next

- Implement sales forecasting using time-series analysis
- Connect to real-time data (SQL or Excel Live Source)

---

## ✅ How to Use

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Clone or download this repository
3. Open `Pizza sales BI Final Draft.pbix` in Power BI Desktop
4. Explore the dashboard interactively using slicers and filters
---
<!--
**Tips:**

After formatting the date and cleaning, I exported data from MySQL. Anyone who wants to export from a direct .csv file may have issues with date formatting. On that case, he can do the following steps --
Transform Data> Power Query Editor>right click on order_date> change type>Text(This will change all the mixed text and date format to text)> Then again right click on order_date> change type>using locale>Data type=Date>Locale=English(World)>OK>Close and Apply. 
I am attaching two screenshots for anyone's convenience.
-->

## 🛠️ Data Cleaning Tip (MySQL/CSV Users)

If you're working with the raw CSV version of the dataset (instead of exporting clean data from MySQL), you might run into **date formatting issues** — especially when `order_date` contains both text and date formats.

### ✅ Fixing Mixed Date/Text Format in Power BI

Follow these steps to clean the `order_date` column inside Power BI:

1. Go to `Transform Data` > `Power Query Editor`
2. Right-click on `order_date` column → **Change Type** → **Text**  
   (This standardizes all values as text)
3. Right-click again on `order_date` → **Change Type** → **Using Locale**
4. In the dialog:
   - **Data Type**: Date  
   - **Locale**: English (World)
5. Click OK → Close & Apply

This will correctly convert all entries into date format without errors or blank.

![image](https://github.com/user-attachments/assets/44c0ea76-dccf-440a-8932-f8e053b290f3)

![image](https://github.com/user-attachments/assets/54688a6a-3812-41ec-a443-c6d52a4413a9)


