#  Cyclistic Bike-Share Case Study

##  Overview

This case study dives into how **casual riders** and **annual members** use Cyclistic bikes differently. The goal? Help Cyclistic grow by turning more casual users into committed annual members. To get there, I followed the six-step data analysis process: **Ask, Prepare, Process, Analyze, Share, and Act**.

##  Business Task

> **How do annual members and casual riders use Cyclistic bikes differently?**
> My task was to uncover insights that could shape a smart marketing strategy to increase annual memberships.

##  Data Source

* 12 months of trip data from Cyclistic (a fictional company based on [Divvy](https://divvybikes.com))
* Publicly available via Divvy at: [https://divvy-tripdata.s3.amazonaws.com/index.html](https://divvy-tripdata.s3.amazonaws.com/index.html)
* Cleaned and explored using Python (Pandas and NumPy)
* The dataset contains no personally identifiable information (PII)

##  Data Cleaning Steps

* Converted timestamps to proper datetime format
* Calculated `ride_length` in minutes
* Removed rows with missing or negative ride durations
* Created new features: `day_of_week` and `start_hour` to help spot patterns

## 📊 Key Insights

| Behavior            | Casual Riders     | Annual Members            |
| ------------------- | ----------------- | ------------------------- |
| **Avg. Duration**   | \~24 minutes      | \~12 minutes              |
| **Ride Timing**     | Weekends, midday  | Weekday mornings/evenings |
| **Bike Preference** | Electric / Docked | Classic                   |

* Casual riders tend to ride longer and mostly on weekends or around midday—suggesting they ride for fun or exploration.
* Members, on the other hand, ride shorter trips more consistently, especially during commute hours on weekdays.
* Casual riders use more electric and docked bikes, while members prefer classic bikes.

##  Visuals That Tell the Story

* **Boxplot** showing ride duration by user type
* **Bar chart** of total rides by day of the week
* **Line chart** showing usage by hour of the day
* **Stacked bar chart** comparing bike type preferences

##  Marketing Recommendations

1. **Leisure Conversion Campaign**
   Casual riders often take longer weekend rides. A targeted campaign could promote how memberships save money on long rides—perfect for tourists and occasional recreational riders.

2. **Commute Incentive Program**
   Since members ride more on weekdays during commute hours, offer weekday-focused perks or trial memberships to casual riders who use the service Monday–Friday.

3. **Classic Bike Awareness**
   Many casual riders stick with electric or docked bikes. Promote the convenience and availability of classic bikes through user stories, in-app promotions, or email tips.

##  Tools Used

* Python (Pandas, Seaborn, Matplotlib)
* Jupyter Notebook
* GitHub for documentation and version control

##  Final Thoughts

This project provided actionable insights into Cyclistic's users. By understanding how casual and member riders differ, we can build marketing strategies that actually fit how people ride. These data-backed recommendations can help Cyclistic grow its member base and deliver more value to its riders.
