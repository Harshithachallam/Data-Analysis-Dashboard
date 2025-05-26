# 🏨 Hotel Performance Dashboard - Power BI

## 📌 Project Objective

The goal of this project is to build an interactive dashboard using Power BI that provides deep insights into hotel performance across multiple dimensions like city, room type, booking platform, and time period. This dashboard helps stakeholders monitor key metrics such as revenue, occupancy, cancellations, and booking trends over time.

---

## 📊 Key Metrics & DAX Measures

The project includes a range of calculated columns and measures written in DAX to analyze hotel data:

### 📅 Calculated Columns
- **Week Number (`wn`)**: Extracts the week number from the date.
- **Day Type**: Classifies each day as either "Weekend" or "Weekday" based on the weekday number.

### 🔢 Measures
1. **Revenue** – Total revenue realized.
2. **Total Bookings** – Number of total bookings.
3. **Total Capacity** – Room capacity across all hotels.
4. **Total Successful Bookings** – Number of successful bookings.
5. **Occupancy %** – Percentage of rooms booked out of total capacity.
6. **Average Rating** – Average customer rating.
7. **No. of Days** – Total number of days in the data range.
8. **Total Cancelled Bookings** – Number of cancelled bookings.
9. **Cancellation %** – Proportion of cancelled bookings.
10. **Total Checked Out** – Number of successful checkouts.
11. **Total No-Show Bookings** – Bookings where the customer didn’t show up.
12. **No-Show Rate %**
13. **Booking % by Platform** – Booking share from platforms like Tripster, LogTrip, etc.
14. **RevPAR** – Revenue per available room.
15. **DBRN** – Daily Booked Room Nights.
16. **DSRN** – Daily Sellable Room Nights.
17. **DURN** – Daily Utilized Room Nights.
18. **WoW Change Metrics** – Week-over-week % change for:
    - Revenue
    - Occupancy
    - ADR (Average Daily Rate)
    - RevPAR
    - Realisation %
    - DSRN

---

## 📈 Project Insights

- **Revenue and Occupancy Trends** are visualized weekly to identify fluctuations.
- **Room Type & City Filters** allow dynamic drill-downs into specific hotel performance.
- **Cancellation and No-Show Rates** help assess operational risks.
- **Booking Platform Contribution** shows the effectiveness of different booking channels.
- **KPIs like RevPAR and Realisation %** are benchmarked for performance comparisons.
- Visual tools like pie charts, line graphs, and bar charts enhance clarity.

---

## ✅ Conclusion

This Power BI dashboard simplifies complex hotel performance data into actionable insights. By using calculated DAX measures and visuals, stakeholders can monitor operational efficiency, optimize booking channels, and improve overall guest experience. It serves as a powerful decision-making tool for hotel managers and analysts.

---

## 🛠 Tools Used

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Interactive Visuals and Filters**
