<h2 align="center">
  Fleet Management Dashboard
</h2>


<h3 align="center">
IN PROGESS
</h3>

<a href="https://app.powerbi.com/view?r=eyJrIjoiY2JkYTc2YjktMTgxZi00NzMzLThiNDMtNGFjNjI0Y2VhMzdhIiwidCI6IjNmMTcwMmFmLTNmNGUtNDk1ZS04YzhiLTEzNzIxZjM5YjFiMCJ9">
  <img src="https://github.com/gentallman/Retail-Supply-Chain-Operations-Management/assets/78334851/ed21a0ff-f400-4a4d-9a6c-80c76bf137e7" alt="Live Project" width="100">
</a>

<br>
<br>


Developed a **Fleet Management Dashboard** tailored for the Canada region, designed to provide in-depth insights into both driver performance and revenue generation. The dashboard is structured into two comprehensive pages: **Driver Insights** and **Revenue Insights**, each offering key metrics and interactive visuals to help stakeholders make data-driven decisions.

### **Driver Insights Page:**
The **Driver Insights** section focuses on monitoring driver performance and operational efficiency. It includes several **Key Performance Indicators (KPIs)** such as:
- **Fuel Consumption (Liters):** The total liters of fuel consumed over a selected period.
- **Number of Drives:** The total number of trips made by drivers.
- **Kilometers Traveled:** Total distance covered by all drivers.
- **Fixed Costs:** The fixed costs associated with operating the fleet.
- **Maintenance Costs:** Costs incurred for vehicle maintenance.
- **Fuel Expenses (in dollars):** The total fuel cost for the fleet.

Additionally, the data is broken down by **driver** and **month**, providing granular insights into performance over time. To enhance interactivity, I built a **custom tooltip** feature for the table visuals. When users hover over a driver’s KPIs, the tooltip reveals additional metrics, including:
- **Total Drives:** The sum of trips completed by the driver.
- **Average Fuel Efficiency (KM per liter):** A calculation of fuel efficiency based on kilometers driven per liter.
- **Total Fuel Consumption per Kilometer:** The fuel consumed per kilometer traveled by the driver.
- **Fuel Cost per Kilometer:** A financial metric showing the fuel cost per kilometer.
- **Average Distance per Trip:** An insight into the average distance covered in each trip.

This page helps fleet managers to assess each driver’s efficiency, optimize fuel consumption, and reduce operational costs by identifying key areas for improvement.

### **Revenue Insights Page:**
The **Revenue Insights** page focuses on the financial performance of the fleet operations, highlighting the revenue generated from deliveries and the overall value of goods transported. Key metrics and features include:
- **Revenue:** Total revenue generated over time, with YoY (Year-over-Year) growth rates.
- **Goods Value:** The total value of goods delivered.
- **Number of Delivered Orders:** The total number of orders completed.
- **Weight (Cubic Meters and Tons):** The total weight of goods transported, broken down in cubic meters and tons.
- **YoY Growth:** Year-over-year growth comparisons for key metrics like revenue, goods value, and number of orders.

The page also includes KPIs for:
- **Customers with Multiple Orders:** A breakdown of customers who placed more than one order.
- **One-Time Orders:** Insights into customers who placed only a single order.

To visualize trends, a **line chart** is used to showcase the breakdown of revenue by different years and months, allowing users to identify seasonality and growth patterns. 

There is also a **map visual**, which displays total revenue by **province**, giving a geographic overview of performance. Additionally, I created a **custom button** that allows users to switch views and see the revenue breakdown by **cities** within the selected province, providing more localized insights.

### **Interactive Slicer Panel:**
Both pages of the dashboard are equipped with a slicer panel, enabling users to filter data by:
- **Truck Type:** Options include box trucks, semi-trailers, full trailers, and tractors.
- **Trailer Type:** Users can choose between dry, fridge, and reefer trailers.

The slicer panel also includes intuitive **"Clear"** and **"Close"** buttons, allowing users to easily reset the filters or close the panel after applying selections.

