# Indian Real Estate Analytics Dashboard

## 📌 Project Overview
The **Indian Real Estate Analytics Dashboard** is a fully interactive multi-page Power BI dashboard designed to analyze and visualize Indian real estate market trends.  
This project transforms raw property listing data into meaningful business insights through dynamic visualizations, KPI tracking, and interactive analytics.

The dashboard focuses on:
- Property Sales & Rentals Analysis
- Pricing Trends
- Property Inventory Insights
- Amenities & Compliance Tracking
- Geographic Distribution of Properties
- Detailed Property-Level Exploration

---

# 🚀 Dashboard Pages

## 1️⃣ Overview Dashboard
The Overview page provides a high-level summary of the real estate market.

### Features:
- Total Properties KPI
- Properties for Sale & Rent
- Average Days on Market (DOM)
- Property Trend Analysis Over Time
- Property Inventory by Age & Listing Type
- Furnishing Distribution Donut Chart
- Amenities Compliance Metrics
- Interactive Map Visualization
- Dynamic Filters & Slicers

### Key Insights:
- Market inventory distribution
- Sales vs Rental trends
- Property availability patterns
- Amenities coverage analysis

---

## 2️⃣ Price Index Dashboard
The Price Index page focuses on property pricing and valuation analysis.

### Features:
- Average & Median Property Prices
- Average Monthly Rental Analysis
- Price per Sq Ft Metrics
- Price Trend Analysis
- Geographic Pricing Distribution
- Amenities Impact on Pricing
- Comparative Price Visualizations

### Key Insights:
- City-wise price comparison
- Rental vs Sale pricing
- Property valuation trends
- Price influence of amenities

---

## 3️⃣ Details Dashboard
The Details page allows detailed property-level exploration.

### Features:
- Interactive Property Table
- Search & Filter Functionality
- Conditional Formatting
- DOM Status Tracking
- Amenities Breakdown
- Furnishing Status Analysis
- Listing Type Categorization

### Key Insights:
- Detailed listing analysis
- Property-specific exploration
- Market performance tracking
- Property feature comparisons

---

# 🛠️ Tools & Technologies Used

- Power BI
- DAX (Data Analysis Expressions)
- Data Visualization
- Data Modeling
- Business Intelligence
- Interactive Dashboard Design

---

# 📊 Key DAX Measures Used

```DAX
Properties For Sale =
CALCULATE(
    DISTINCTCOUNT('india_real_estate_dataset'[Property ID]),
    'india_real_estate_dataset'[Listing Type] = "Sale"
)

Properties For Rent =
CALCULATE(
    DISTINCTCOUNT('india_real_estate_dataset'[Property ID]),
    'india_real_estate_dataset'[Listing Type] = "Rental"
)

Average DOM =
AVERAGE('india_real_estate_dataset'[Days on Market (DOM)])

Avg Price per Sq Ft =
AVERAGE('india_real_estate_dataset'[Price Per SqFt])
```

---

# 🎨 Dashboard Design Highlights

- Modern and minimal UI
- Custom color palette
- Rounded card layouts
- Interactive navigation buttons
- Multi-page dashboard structure
- Professional visual hierarchy
- Responsive slicers and filters

---

# 📍 Dataset Information

The dashboard uses an Indian Real Estate dataset containing:
- Property Listings
- Sales & Rental Data
- Property Prices
- Furnishing Details
- Amenities Information
- Location Coordinates
- Property Age Classification
- Market Performance Metrics

---

# 📈 Business Use Cases

This dashboard can help:
- Real Estate Analysts
- Property Investors
- Real Estate Agencies
- Business Intelligence Teams
- Market Researchers
- Property Consultants

to make data-driven decisions using real-time property insights.

---

# 📌 Key Skills Demonstrated

✅ Data Cleaning  
✅ Data Modeling  
✅ DAX Calculations  
✅ Interactive Dashboard Design  
✅ Power BI Visualization  
✅ Business Intelligence Reporting  
✅ UI/UX Dashboard Styling  
✅ Analytical Thinking  

---

# 📬 Connect With Me

If you like this project or want to collaborate on Power BI & Data Analytics projects, feel free to connect with me.

⭐ Don’t forget to star this repository if you found it useful!
