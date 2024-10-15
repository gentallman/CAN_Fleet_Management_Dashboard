<h2 align="center">
  Fleet Management Dashboard
</h2>

<p align="center">
  <img src="https://github.com/user-attachments/assets/fdef5d46-5966-494b-9e14-43b8861ba38e" width="60"><br> 
  <img src="https://github.com/user-attachments/assets/a32a3efc-302c-4cdb-a1dc-1b43a5c86709" width="430">
</p>


<p align="center">
<a href="https://app.powerbi.com/view?r=eyJrIjoiY2JkYTc2YjktMTgxZi00NzMzLThiNDMtNGFjNjI0Y2VhMzdhIiwidCI6IjNmMTcwMmFmLTNmNGUtNDk1ZS04YzhiLTEzNzIxZjM5YjFiMCJ9">
    <img src="https://github.com/user-attachments/assets/eb030d5f-8bb3-458e-9a2b-3c13a455c662" alt="Live Project" width="120">
</a>
</p>


<br>

<div align="justify"> 

### **Problem Statement:**

In the Canadian fleet management industry, optimizing both driver performance and revenue generation is essential for long-term success. Fleet operators must have a deep understanding of key operational metrics, such as fuel consumption, cost efficiency, and revenue distribution, to ensure smooth and profitable operations. Additionally, fostering customer loyalty and maximizing repeat business is critical to maintaining a competitive edge and driving growth.

For effective decision-making, fleet operators require a comprehensive and interactive dashboard that enables them to monitor and analyze essential KPIs related to driver performance, operational costs, and revenue metrics. Moreover, customer engagement and retention strategies must be aligned with the business's revenue objectives to ensure sustained growth. The current challenge is to provide a clear, actionable insight into both driver behavior and financial performance, along with strategies to boost customer loyalty and retention.

### **Objective:**

The objective of this project is to develop a **Fleet Management Dashboard** for the Canada region that offers actionable insights into both driver performance and revenue generation. The dashboard will have two primary components:

1. **Driver Insights:** 
   - Track and analyze critical KPIs such as fuel consumption, number of drives, kilometers traveled, fixed costs, and maintenance expenses.
   - Provide detailed breakdowns by individual drivers and months to allow for in-depth analysis.
   - Include custom tooltips to offer additional driver-specific metrics such as average fuel efficiency, fuel consumption per kilometer, and more.

2. **Revenue Insights:**
   - Visualize total revenue, goods value, delivered orders, and weight transported, with year-over-year (YoY) growth metrics.
   - Identify trends in customer behavior, focusing on repeat orders and one-time customers.
   - Provide an interactive map to display revenue by province and allow users to drill down into city-level insights.
   - Incorporate a line chart to show revenue growth by different years and months.

3. **Customer Loyalty Insights:**
   - Provide insights into customer behavior, particularly the balance between repeat and one-time customers.
   - Offer actionable recommendations for customer retention strategies, upselling, cross-selling, and loyalty program implementation.

### Data Modeling and Relationship

Implemented the necessary calculated measures and columns to enhance data analysis capabilities. Established relationships between multiple tables to ensure proper data integration and enable seamless analysis across different datasets. This process involved defining the appropriate keys and ensuring the accuracy and integrity of the data model

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

<br>

## Contact

Author: [@Smit Rana](https://www.linkedin.com/in/smit98rana/) 
<p align="center">
	<img src="https://user-images.githubusercontent.com/74038190/214644145-264f4759-7633-441e-9d67-d8dda9d50d26.gif" width="200">
</p>

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&center=true&vCenter=true&random=true&width=435&lines=I+hope+this+work+serves+you+well!" alt="Typing SVG" />
  </a>
</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" >
