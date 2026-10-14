# 🚖 Ride Sharing and Cab Booking Analytics | Power BI Dashboard

An interactive **Power BI dashboard** designed to analyze ride-sharing and cab booking operations, revenue performance, customer behavior, payment preferences, and ride cancellation patterns across multiple cities.

This project transforms ride booking data into meaningful insights through interactive visualizations, key performance indicators (KPIs), and city-wise comparisons.

## 📊 Dashboard Preview

![Ride Sharing and Cab Booking Analytics Dashboard](dashboard.png)

## 🎯 Project Objectives

- Analyze total rides and overall revenue performance.
- Monitor average fare and customer ratings.
- Understand ride cancellation patterns and ride status distribution.
- Compare payment method preferences among customers.
- Evaluate ride demand across different days.
- Compare vehicle types and city-wise performance.
- Support data-driven decisions to improve operational efficiency and customer experience.

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard development and data visualization.
- **Power Query** — Data cleaning and transformation.
- **DAX (Data Analysis Expressions)** — KPI calculations and analytical measures.
- **CSV / Tabular Data** — Data source for ride booking analysis.
- **GitHub** — Project documentation and version control.

## 📌 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Rides | 800 |
| Total Revenue | 124K |
| Average Fare | 154.55 |
| Average Rating | 4.00 |
| Cancellation Rate | 21.50% |

*Note: KPI values are based on the dashboard displayed in this project. Revenue is displayed in the dashboard's original units.*

## 📈 Dashboard Visualizations

### 1. Total Rides by Day
A line chart showing daily ride volumes and variations in booking demand. It helps identify changes in ride activity over time.

### 2. Total Rides by Payment Method
A doughnut chart comparing ride payments made through:
- UPI
- Cash
- Wallet
- Card

This visualization helps understand customer payment preferences.

### 3. Total Rides by City and Ride Status
A stacked bar chart comparing ride statuses across cities, including:
- Completed
- Cancelled by Customer
- Cancelled by Driver

It helps identify differences in booking outcomes across locations.

### 4. Total Rides by Vehicle Type
A horizontal bar chart comparing ride volumes across vehicle categories, including:
- Bike
- Mini
- SUV
- Auto

This provides a view of demand across different vehicle options.

### 5. City-wise Average Fare Analysis
A matrix comparing average fares for different vehicle types across cities, with totals for city and vehicle-level comparisons.

## 🔍 Key Insights

Based on the displayed dashboard:

- **800 total rides** provide an overview of the booking activity represented in the report.
- **21.50% cancellation rate** highlights an opportunity to investigate booking cancellations and improve ride completion.
- **4.00 average rating** provides a high-level view of customer satisfaction.
- **Payment method distribution** helps compare the use of UPI, cash, wallets, and cards.
- **Vehicle-wise ride comparisons** help identify which categories attract more bookings.
- **City-level comparisons** help assess differences in demand, ride outcomes, and average fares.

These observations can help guide further analysis of driver availability, cancellation reasons, customer preferences, and city-level operational performance.

## 🎛️ Interactive Features

The dashboard includes interactive filters for:

- City
- Vehicle Type
- Payment Method
- Ride Status

These filters allow users to explore the data from different perspectives and compare ride performance across selected categories.

## 📂 Project Structure

```text
cab-booking-analytics/
│
├── README.md
├── dashboard.png
├── cab_booking_data.csv
└── Cab booking analytics.pbix
```

| File | Description |
|---|---|
| `README.md` | Project documentation |
| `dashboard.png` | Dashboard screenshot displayed in this README |
| `cab_booking_data.csv` | CSV dataset used for analysis, if applicable |
| `Cab booking analytics.pbix` | Power BI report file |

## 🚀 How to Use This Project

1. Clone or download this GitHub repository.
2. Install [Microsoft Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop).
3. Open `Cab booking analytics.pbix`.
4. If prompted, update the data source path to the location of the CSV file.
5. Refresh the data if required.
6. Use the dashboard filters to explore rides, revenue, payment methods, vehicle types, and cancellation patterns.

**Important:** The included CSV should match the data model expected by the PBIX file. If the dataset has been reconstructed or replaced, some existing visuals or measures may require adjustments.

## 💡 Business Applications

This dashboard demonstrates how data analytics can support:

- Ride demand monitoring.
- Revenue and fare analysis.
- Cancellation pattern investigation.
- Customer experience monitoring.
- Vehicle category performance comparisons.
- City-level operational planning.

## 🔮 Future Improvements

- Add monthly and year-over-year performance analysis.
- Include driver performance and customer segmentation.
- Analyze cancellation reasons and peak booking hours.
- Introduce profitability and operational cost metrics.
- Add geographic maps to visualize ride demand by location.
- Develop forecasting models to predict future ride demand.
- Automate data refresh and reporting workflows.

## 👨‍💻 Skills Demonstrated

- Data visualization and dashboard design
- Data cleaning and transformation
- KPI development and analytical calculations
- Business intelligence and exploratory data analysis
- Interactive reporting using Power BI
- Data storytelling and insight communication
- Project documentation using GitHub

## 📌 Project Note

This project is intended for educational and portfolio purposes. KPI values shown above reflect the supplied dashboard. Verify the underlying dataset and calculations before using the results for business decisions. If sample or synthetic data is used, it should be clearly identified as such.

## ⭐ Feedback

If you find this project useful, consider giving the repository a ⭐ on GitHub.

Suggestions and feedback for improving the dashboard are welcome!
