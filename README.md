# 🚕 Uber Ride Data Analysis – Power BI Dashboard

This project analyzes Uber ride data to uncover usage patterns, trip purposes, peak travel hours, and category-wise distribution. The dashboard helps users and stakeholders understand ride behaviors across time and purposes.

## 📊 Dashboard Overview
The Power BI dashboard includes the following:
### 🔹 KPIs:
- **Total Trips:** 1,140
- **Total Distance Traveled:** 18.5 miles
- **Average Duration:** 22.68 minutes
- **Morning Trips:** 313
- **Afternoon Trips:** 558
- **Evening Trips:** 233
- **Night Trips:** 37
- **Most Booked Day:** Friday

### 🔹 Visuals:
- **Donut Chart:** Trips by Category (Business vs. Personal)
- **Bar Chart:** Trips by Purpose (e.g., Meeting, Meal/Entertainment)
- **Stacked Column Chart:** Trips by Month and Purpose
- **Matrix Table:** Purpose breakdown across weekdays
- **Slicer Filters:** By Month, Category, and Shift Timing
- 
## 🔍 Key Insights
1. 🏷️ **Category Dominance:** 93.4% of rides are for **Business** purposes.
2. 🎯 **Most Common Purpose:** **Meeting** rides dominate trip purposes.
3. 🕑 **Peak Hours:** Most trips occur between **12 PM–1 PM** and **4 PM–7 PM**.
4. 📆 **Busiest Day:** **Friday** has the highest ride volume.
5. 📊 **Busiest Month:** **December** is the most active month for rides.
6. 🌞 **Trip Time Breakdown:** Afternoon rides are the most common.
7. ⏱️ **Average Duration:** Each trip lasts ~23 minutes.
8. 🛣️ **Distance:** 18.5 miles of total recorded travel.
9. 📅 **Weekday Patterns:** Trips for meetings are more common on weekdays, especially Fridays.

## 📁 Files

-<a href="https://github.com/Rupali-2001/Uber-Ride-Data-Analysis/blob/main/Dashboard.jpg">Dashboard</a>

-<a href="https://github.com/Rupali-2001/Uber-Ride-Data-Analysis/blob/main/uber_dataset_dashboard.pbix">Power_bi_Dashboard File</a>

-<a href="https://github.com/Rupali-2001/Uber-Ride-Data-Analysis/blob/main/Uber_Dataset_Cleaned.xlsm">Uber_dataset</a> 

## ⚙️ Tools Used

- **Power BI Desktop**
- **DAX for KPIs and Measures**
- **Custom Visuals and Slicers**

## 📌 How to Use

1. Open the `.pbix` file using Power BI Desktop.
2. Use slicers to filter by Month, Category, or Shift Timing.
3.Hover over the visuals to explore trip details.
4. Use the Matrix to view purpose-wise distribution across weekdays.

## 📥 Future Enhancements

- Add geolocation maps for pickup/drop analysis
- Integrate real-time ride data (if available)
- Predictive analysis on peak ride demand

## 🚧 Challenges Faced

- 🔄 **Data Cleaning:** The raw dataset required preprocessing—parsing date/time fields, handling missing values, and calculating derived metrics like duration and speed.
- 🧠 **DAX Formulas:** Creating custom KPIs using DAX (e.g., Most Booked Day, Average Speed) involved trial and error with functions like `CALCULATE`, `RANKX`, and `FORMAT`.
- 🎨 **Dashboard Layout:** Designing a visually appealing and user-friendly dashboard layout while maintaining clarity and responsiveness.
- ⏱️ **Time Categorization:** Accurately segmenting rides into time-of-day categories (morning, afternoon, evening, night) based on start hour.
- 📊 **Purpose Distribution:** Some categories had too few data points, making it challenging to display meaningful insights.

## ✅ Conclusion
This Uber Ride Data Analysis project provided valuable insights into ride patterns, usage purposes, and user behavior. The Power BI dashboard enables users to interactively explore:
- Most common trip purposes
- Category-wise ride distribution (Business vs. Personal)
- Peak booking hours and days
- Month-over-month trip trends

Through this project, I deepened my understanding of DAX, data modeling, and dashboard storytelling—resulting in a comprehensive and visually impactful Power BI solution.



