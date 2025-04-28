
---

# 🚲 Bike Share Trip Analysis

## 📋 Project Overview
This project explores and analyzes a bike-share system’s trip data to uncover the factors that affect trip duration, and how user behavior varies across different groups.  
It also provides business insights to help improve operational efficiency and customer retention strategies.

---

## 📊 Features (Dataset Columns)
| Column Name                | Description |
|-----------------------------|-------------|
| `duration_sec`              | Duration of the trip in seconds |
| `start_time`                | Start date and time of the trip |
| `end_time`                  | End date and time of the trip |
| `start_station_id`          | ID of the station where the trip started |
| `start_station_name`        | Name of the station where the trip started |
| `start_station_latitude`    | Latitude of the start station |
| `start_station_longitude`   | Longitude of the start station |
| `end_station_id`            | ID of the station where the trip ended |
| `end_station_name`          | Name of the station where the trip ended |
| `end_station_latitude`      | Latitude of the end station |
| `end_station_longitude`     | Longitude of the end station |
| `bike_id`                   | ID of the bike used for the trip |
| `user_type`                 | Type of user - Subscriber (member) or Customer (casual rider) |
| `member_birth_year`         | Birth year of the member (if available) |
| `member_gender`             | Gender of the member (if available) |
| `bike_share_for_all_trip`   | Whether the user opted for bike-share service for the entire trip |

---

## ❓ Business Questions Addressed
1. **How long does the average trip take?**
2. **Is the trip duration affected by weather (using months/seasons)?**
3. **Does trip duration depend on user type (Subscriber vs Customer)?**

---

## 🔎 Summary of Findings
- **Average Trip Duration**: Most trips are relatively short, but casual users tend to have longer rides than subscribers.
- **Impact of Weather/Seasons**: Trip duration remains fairly consistent across different months, meaning weather has minimal effect.
- **User Type Analysis**: Casual customers (Customers) are more likely to take longer trips compared to Subscribers (Members).
- **Business Strategy**: Focus on converting casual riders to subscribers to enhance customer lifetime value. Also, promote longer rental plans during peak seasons to maximize bike usage.

---

## 🛠️ How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bike-share-trip-analysis.git
   ```
2. Navigate into the project directory:
   ```bash
   cd bike-share-trip-analysis
   ```
3. Open the analysis Jupyter Notebook and run the cells to explore the results.

---

## 📈 Key Visualizations
- **Trip Duration Distribution**
- **Trip Duration by Month/Season**
- **Trip Duration Comparison by User Type**
- **User Demographics (Gender & Age Distribution)**

---

## 📑 Conclusion
By understanding how trip patterns vary based on user type and seasonality, bike-share companies can better target marketing efforts, adjust pricing strategies, and improve bike availability, ultimately increasing overall customer satisfaction and revenue.

---

## ✍️ Author
- Jay Bharamu Shahapurakar

---
