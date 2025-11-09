# 🚕 Cab Booking System Data Analysis with SQL

## **📝 Purpose**

This project, completed as part of my **Masters in Data Science and Analytics with AI from ITVEDANT**, focuses on designing and querying a relational database schema for a cab booking system[cite: 7]. [cite_start]The primary goal is to extract valuable business insights by analyzing customer booking trends, driver performance, and revenue metrics[cite: 6, 9]. By leveraging SQL, this case study provides stakeholders with data-driven insights to optimize operations, improve customer satisfaction, and maximize profitability.

---

## **🛠️ Tech Stack**

**SQL** (Used for all data querying and analysis [cite: 49])
**MySQL Workbench** (Database environment used for query execution [cite: 52])

## **📂 Data Source**

The data is sourced from a simulated **Cab Booking System** database.

The database consists of the following entities (tables):
* `Bookings`
* `Customers`
* `Cabs`
* `Drivers`
* `TripDetails`

---

## **💡 Features and Insights**

This project addresses various business problems across customer analysis, driver performance, revenue, and operational efficiency, aiming to improve the efficiency of the cab booking system.

### **1. Business Problem**

The cab service company needs to enhance its operations by monitoring bookings, tracking customer preferences, evaluating driver efficiency, analyzing revenue trends, and identifying operational bottlenecks.

### **2. Goal of the Analysis**

The analysis is structured to answer key business questions across five domains:

* **Customer & Booking Analysis:** Understand customer booking frequency and cancellation behavior.
* **Driver Performance & Efficiency:** Evaluate driver ratings, trip distance contribution, and cancellation rates.
* **Revenue & Business Metrics:** Calculate total revenue and identify high-volume, high-fare routes and correlations.
* **Operational Efficiency:** Analyze average waiting times and common reasons for trip cancellations.
* **Comparative Analysis:** Compare revenue across different cab types and analyze demand differences between weekdays and weekends.

### **3. Business Impact & Key Insights**

The analysis provided specific, actionable insights for strategic decision-making:

| Analysis Area | Key Insight | Business Impact |
| :--- | :--- | :--- |
| **Peak Demand** | **Monday** and **Tuesday** are the busiest days of the week (9 bookings each)[cite: 293, 294, 295, 296]. | Focus on optimizing **cab availability** and implementing **dynamic pricing** on these days to meet peak demand. |
| **Driver Performance** | Drivers **Deepak Rao (2.90)** and **Arjun Rana (2.50)** have below-average ratings. | [cite_start]Implement **targeted training programs** to improve the performance and rating of low-rated drivers. |
| **High Cancellation Risk** | [cite_start]Cancellation reasons like **Driver late**, **Driver unavailable**, and **Traffic jam** are operational issues[cite: 556, 560, 562]. | [cite_start]Address **Driver punctuality** and implement **Dynamic routing/communication** to reduce the likelihood of cancellations. |
| **Revenue Correlation** | [cite_start]Higher-rated drivers (**Farhan Ali: 4.9, $1000.00**; **Amit Singh: 4.3, $1140.50**) tend to earn higher total fares. | **Incentivize high ratings** as it correlates positively with driver productivity and total revenue. |
| **Operational Bottlenecks** | [cite_start]**Sion** (4984.00 minutes) and **Lower Parel** (4926.00 minutes) have the longest average waiting times. | Allocate **More cabs** or use **Predictive modeling** to preposition drivers in these high-delay areas to reduce customer wait times. |
| **Demand Differences** | **Weekday bookings** (34 total, $6960.50 revenue) significantly outweigh **Weekend bookings** (11 total, $2000.00 revenue). | Introduce **Dynamic pricing** to capitalize on the higher weekday demand and potentially offer weekend promotions. |

---

## **📸 Screenshots**

This section contains snapshots of the database tables used and the SQL queries with their result grids, demonstrating the analytical process.

### **A. Database Tables**

| Table Name | Screenshot Tag (Reference Page) |
| :--- | :--- |
| `Bookings` | [Link](https://github.com/YashMastakar/Cab-Booking-SQL-Analysis/blob/main/Table%201.png) |
| `Customers` | [Link](https://github.com/YashMastakar/Cab-Booking-SQL-Analysis/blob/main/Table%202.png) |
| `Cabs` | [Link](https://github.com/YashMastakar/Cab-Booking-SQL-Analysis/blob/main/Table%203.png) |
| `Drivers` | [Link](https://github.com/YashMastakar/Cab-Booking-SQL-Analysis/blob/main/Table%204.png) |
| `TripDetails` | [Link](https://github.com/YashMastakar/Cab-Booking-SQL-Analysis/blob/main/Table%205.png) |

### **B. Questions and Queries**

| Problem Area | Business Question | Query & Result Screenshot Tag (Reference Page) |
| :--- | :--- | :--- |
| **Customer Analysis** | Q1: Customers who completed the most bookings. | `` (Page 8) |
| | Q3: Busiest day of the week for bookings. | `` (Page 9) |
| **Driver Performance** | Q1: Drivers with an average rating below 3.0. | `` (Page 9) |
| | Q2: Top 5 drivers with the longest trips by distance. | `` (Page 10) |
| | Q3: Drivers with a high percentage of canceled trips. | `` (Page 10) |
| **Revenue & Business Metrics** | Q1: Total revenue generated in the last 6 months. | `` (Page 11) |
| | Q3: Correlation between driver ratings and earnings. | `` (Page 12) |
| **Operational Efficiency** | Q1: Average waiting time for different pickup locations. | `` (Page 13) |
| | Q2: Most common reasons for trip cancellations. | `` (Page 13) |
| **Comparative Analysis** | Q3: Weekend vs. weekday bookings and revenue. | `` (Page 16) |

***

