
# Power BI Report Layout & Interactivity Guide

## 📁 Data Setup
1. Import the Excel file: `Financial Sample.xlsx`
2. Clean column names (remove leading spaces, format date as `Date/Time`)
3. Create calculated field: `Month-Year = FORMAT([Date], "MMM YYYY")`

---

## 📊 Suggested Pages and Visuals

### 1️⃣ Overview Page
- **Profit by Segment** – Clustered bar chart
- **Sales Over Time** – Line chart
- **Top 5 Products by Profit** – Bar chart (TopN filter)
- Add summary cards: Total Sales, Profit, Avg Units Sold

### 2️⃣ Product Performance Page
- **COGS vs Sales by Product** – Stacked bar chart
- **Discount Impact on Sales** – Scatter plot (Segment as legend)

### 3️⃣ Geography & Trends Page
- **Profit by Country** – Map or bar chart
- **Monthly Profit Trend** – Line chart (Month-Year axis)

---

## 🖱 Interactive Features

### 🟦 Buttons
- Create navigation buttons:
  - "Home", "Product Insights", "Geo & Time Trends"
  - Use Action → Page Navigation

### 🔖 Bookmarks
- Create view toggles:
  - Segment vs Product
  - Profit vs Sales
- Link bookmarks with buttons via Selection Pane

### 🖼 Images
- Add logos or icons
- Align neatly in page corners

---

## 🎨 Design & Formatting
- Color theme: Blue-Grey
- Font: Segoe UI or Calibri (Size 11–14)
- Use slicers at top (e.g., Year, Segment)
- Align and space visuals evenly for clarity
