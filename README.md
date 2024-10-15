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

Built necessary calculated measures and columns and join different tables with relationship

![image](https://github.com/user-attachments/assets/d818353b-44ce-475d-93be-37e0d3a5d02c)

### **Driver Insights Page:**

![2](https://github.com/user-attachments/assets/57fb41fa-a154-4494-8e7f-77c47af4b9a4)

**KPIs** : The **Driver Insights** section focuses on monitoring driver performance and operational efficiency. It includes several **Key Performance Indicators (KPIs)** such as:
- **Fuel Consumption (Liters):** The total liters of fuel consumed over a selected period.
- **Number of Drives:** The total number of trips made by drivers.
- **Kilometers Traveled:** Total distance covered by all drivers.
- **Fixed Costs:** The fixed costs associated with operating the fleet.
- **Maintenance Costs:** Costs incurred for vehicle maintenance.
- **Fuel Expenses (in dollars):** The total fuel cost for the fleet.

Additionally, the data is broken down by **driver** and **month**, providing granular insights into performance over time. 

To enhance interactivity, I built a **`Custom Tooltip`** feature for the table visuals. 

<p align="center">
  <img src="https://github.com/user-attachments/assets/04509610-0a19-4d44-9fe4-aa63fc2b9d25" alt="Live Project" width="500">
</p>

When users hover over a driver’s KPIs, the tooltip reveals additional metrics, including:
- **Total Drives:** The sum of trips completed by the driver.
- **Average Fuel Efficiency (KM per liter):** A calculation of fuel efficiency based on kilometers driven per liter.
- **Total Fuel Consumption per Kilometer:** The fuel consumed per kilometer traveled by the driver.
- **Fuel Cost per Kilometer:** A financial metric showing the fuel cost per kilometer.
- **Average Distance per Trip:** An insight into the average distance covered in each trip.

This page helps fleet managers to assess each driver’s efficiency, optimize fuel consumption, and reduce operational costs by identifying key areas for improvement.

### **Revenue Insights Page:**

![3](https://github.com/user-attachments/assets/ad40ea39-b1ae-4edb-81e4-33afcfc91c58)

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

### Map Visual:

<p align="center">
  <img src="https://github.com/user-attachments/assets/c52e102d-16ee-44aa-8d12-62553fe9fac8" alt="Live Project" width="500">
</p>

There is also a **map visual**, which displays total revenue by **province**, giving a geographic overview of performance. 
Additionally, I created a **`Custom Button`** that allows users to switch views and see the revenue breakdown by **cities** within the selected province, providing more localized insights.

### **Interactive Slicer Panel:**

<p align="center">
  <img src="https://github.com/user-attachments/assets/b803a025-bb8e-4fca-825e-bfe10741fe8d" width="500">
</p>

Both pages of the dashboard are equipped with a slicer panel, enabling users to filter data by:

<p align="center">
  <img src="https://github.com/user-attachments/assets/d0acc3c0-68ae-46d7-9c09-d761053d684b" width="150">
</p>

- **Truck Type:** Options include box trucks, semi-trailers, full trailers, and tractors.
- **Trailer Type:** Users can choose between dry, fridge, and reefer trailers.

The slicer panel also includes intuitive **"Clear"** and **"Close"** buttons, allowing users to easily reset the filters or close the panel after applying selections.


**With a considerable number of customers placing multiple orders, it is important to emphasize customer retention strategies.**

### **Maximizing Customer Loyalty: Effective Strategies for Retention and Growth**
From the data, it’s evident that customers placing multiple orders significantly outnumber those with single orders. This indicates a solid base of repeat or loyal customers—a positive signal for the business, suggesting strong customer retention and repeat business generation. Based on this insight, several key strategies are recommended:

- **Customer Retention Strategies:** With a substantial portion of customers placing repeat orders, it's crucial to prioritize retention efforts. Implement loyalty programs, personalized communications, and excellent customer service to foster repeat business and maintain customer loyalty.
  
- **Upselling and Cross-Selling Opportunities:** Leverage the data on multiple orders to identify opportunities for upselling and cross-selling. By analyzing customer purchase patterns, you can recommend complementary products or services, increasing the average order value.

- **Customer Engagement:** Maintain consistent engagement with customers through email campaigns, newsletters, or social media. Regular updates on new products, promotions, and company news can help encourage repeat purchases.

- **Feedback and Reviews:** Encourage satisfied customers to leave feedback and reviews. Positive reviews can attract new customers while strengthening loyalty among existing ones.

- **Targeted Marketing:** Use purchase history and behavior data to segment customers and create targeted marketing campaigns. Offering personalized promotions and incentives can further encourage repeat purchases.

- **Customer Journey Analysis:** Examine the customer journey from the first purchase to subsequent orders. Identifying and resolving any pain points will enhance the overall experience, ensuring customers return for future business.

- **Customer Support:** Providing top-notch customer support can make a significant difference. Swiftly addressing any concerns or issues helps ensure customer satisfaction and loyalty.

- **Referral Programs:** Motivate your satisfied customers to refer others by offering referral incentives, which can help expand your customer base.

- **Competitor Analysis:** Monitor your competitors to understand why customers choose your business. This knowledge can be used to further refine and improve your offerings, making your brand even more attractive to potential customers.

Focusing on retention, engagement, and customer satisfaction will help the business capitalize on its base of repeat customers, driving long-term growth and success.

