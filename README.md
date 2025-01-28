# Demand Forecasting Analysis for Meal Delivery Company 🍱📊  
**Power BI Dashboard & PPT Integration**  

![PPT Cover Slide](images/ppt_cover.png)  
*Example: Cover slide from the PowerPoint presentation.*

---

## 📌 **Project Overview**  
This project aligns with the **structure and goals** outlined in the PowerPoint presentation. It focuses on forecasting weekly demand for a meal delivery company to optimize raw material procurement and staffing. Below is a breakdown of how this repository maps to your PPT content:

---

## 📄 **PPT-to-README Alignment**  
### **1. Problem Statement**  

> *"Procurement planning is critical due to perishable raw materials. Accurate forecasts help plan stock and staffing."*  

**Solution in This Project**:  
- Built a **Power BI dashboard** to visualize historical trends and forecast future demand.  
- Integrated **AI-driven forecasts** for the next 5 weeks (by center, city, and meal category).  

---

### **2. Data Sources**  
*From PPT:*  
Three datasets were provided:  
1. Historical demand for product-center combinations  
2. Product features (category, price, discounts)  
3. Fulfillment center details (area, city)  

**How It’s Used Here**:  
- Data cleaned and modeled in Power BI (see relationships below).  
- Metrics like *revenue*, *discount %*, and *top categories* calculated using DAX.  

![Data Model](images/data_model.png)  
*Matching PPT’s data schema explanation (Slide 4).*

---

### **3. Key Questions Addressed**  
*From PPT:*  
1. Total orders, revenue, and discount metrics  
2. Top 5 selling categories  
3. Impact of center area on orders  
4. **5-week forecasts**  

**Dashboard Implementation**:  
- **Total Orders/Revenue Panel**:  
  ![Revenue Slide](images/revenue_slide.png)  
  *Mirrors PPT’s Slide 6 (Revenue Analysis).*  

- **Top Categories Visualization**:  
  ![Top Categories](images/top_categories.png)  
  *Matches PPT’s Slide 8 (Top 5 Categories).*  

- **Operational Area Impact**:  
  ![Area Impact](images/area_impact.png)  
  *Aligns with PPT’s Slide 9 (Center Size vs. Orders).*  

- **5-Week Forecast Table**:  
  ![Forecast Slide](images/forecast_slide.png)  
  *Directly answers PPT’s Slide 10 (Next 5 Weeks Forecast).*  

---

## 🛠 **How to Use This Repository**  
### **1. Power BI Dashboard**  
- Open `meal_delivery_forecast.pbix` in Power BI Desktop.  
- **Interactive Filters**:  
  - Slice data by city, meal category, or week.  
  - Drill down from city → center → meal type.  

![Interactive Dashboard](images/dashboard_demo.gif)  
*Mirrors PPT’s Slide 12 (Dashboard Walkthrough).*  

### **2. Data & Code**  
- Raw data in `/data` folder (same as PPT’s datasets).  
- DAX formulas replicate the logic described in PPT’s methodology slides.  

---

## 📊 **Key Results (Matching PPT)**  
| PPT Slide | Insight | Image |  
|-----------|---------|-------|  
| Slide 7 | Total Discount % = **12%** | ![Discount](images/discounts.png) |  
| Slide 11 | Metro centers handle **2.3x more orders** | ![Metro vs Rural](images/metro_vs_rural.png) |  

---

## 📂 **Repository Structure**  
