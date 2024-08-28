# E-commerce-Delivery-Optimization

## Introduction

In today's fast-paced e-commerce environment, timely and cost-effective delivery is crucial to maintaining customer satisfaction and staying competitive. This project aims to optimize the shipping processes for an Indian e-commerce company that relies on two logistic providers. By carefully analyzing the logistics data, this project seeks to minimize delivery times and reduce shipping costs, ensuring that the company meets its delivery targets efficiently.

## Problem Statement

The project focuses on optimizing shipping costs and delivery times for an e-commerce Indian company that utilizes two logistic providers. The primary objective is to achieve specified delivery targets with a priority on minimizing days to delivery. If the origin and destination are the same, the target delivery time is 2 days; otherwise, it is 4 days. The secondary objective is to reduce overall shipping costs while maintaining optimal delivery efficiency.

## Objectives

1. **Minimize Days to Delivery**: Ensuring shipments reach customers within 2 days when the origin and destination are identical, and within 4 days for other shipments.

2. **Optimize Shipping Costs**: Reducing shipping expenses while meeting the specified delivery targets.

## Data Analysis

This project evaluates the performance of two logistics providers, FastWheels and Ship2Home, in terms of shipping costs and delivery times across both local and outstation routes. 

### Average Total Logistic Cost of Providers for Different Shipping Routes
![Pivot Table-1](https://github.com/user-attachments/assets/2298edd9-008c-49b4-9a75-950de9e69567)

- **Local Routes:** FastWheels offers lower logistics costs compared to Ship2Home, especially for routes like Bangalore-Bangalore (₹150.12 vs. ₹188.04).
- **Outstation Routes:** The cost difference between FastWheels and Ship2Home varies, with FastWheels being more economical on some routes (e.g., Bangalore-Delhi).
- **Overall Costs:** FastWheels generally has a lower average total cost across both local and outstation routes compared to Ship2Home.

### Average Delivery Days of Providers for Different Shipping Routes
![Pivot Table-2](https://github.com/user-attachments/assets/7a2d333d-9695-41e6-8dd9-0d132c1b80dc)

- **Local Routes:** FastWheels delivers faster than Ship2Home, with an average of 1.9 days compared to 3.2 days on the Bangalore-Bangalore route.
- **Outstation Routes:** FastWheels generally delivers quicker on most outstation routes, but Ship2Home is faster on certain routes like Delhi-Chennai.
- **Overall Delivery Times:** FastWheels has a lower average delivery time (3.6 days) across both local and outstation routes compared to Ship2Home (4.5 days).

### Final Distribution of Orders 
![Optimized Solution](https://github.com/user-attachments/assets/68088ecd-0398-4470-8bf6-1968a2638e79)

- **Local Shipping Routes:** FastWheels is optimally chosen for 92% of local orders, meeting the target delivery time of 2 days with an average cost of ₹233. Delhi-Delhi is the highest at 99% usage.
- **Outstation Shipping Routes:** FastWheels is selected for 40% of outstation orders, meeting the 4-day target with an average cost of ₹197. The Delhi-Bangalore route has the highest usage at 75%.
- **Cost Efficiency:** The solution balances cost and delivery time, with FastWheels providing a reasonable cost for both local and outstation routes while achieving the delivery targets.
- **Order Distribution:** The higher the percentage of orders allocated to FastWheels, the more it aligns with the optimal delivery times, particularly on local routes.
- **Strategic Insight:** The analysis suggests prioritizing FastWheels for local routes where it meets delivery targets more efficiently and selectively using it for outstation routes based on specific delivery needs.

### Insights From Goal Seek What-If Analysis
![Problem Statement   Objective](https://github.com/user-attachments/assets/ef6b5977-0085-45fd-898b-0ea62c7f3b25)

- **Order Distribution:** FastWheels handles a significant portion of orders, particularly on local routes, where it manages up to 85% of orders for Bangalore-Bangalore and 99% for Delhi-Delhi. For outstation routes, the distribution is more varied, with lower percentages, such as 6% for Delhi-Chennai and a higher percentage of 75% for Delhi-Bangalore.
- **Cost Comparison:** FastWheels generally offers a lower average total logistic cost, especially in local shipping. For example, Bangalore-Bangalore costs ₹113, while Ship2Home costs ₹163. However, on certain outstation routes like Delhi-Kolkata, Ship2Home provides a lower cost.
- **Delivery Time:** FastWheels consistently offers faster delivery times across all routes. For example, in local routes, it delivers in 1.9 to 2 days, compared to Ship2Home’s 2.6 to 3.6 days. The trend continues in outstation routes where FastWheels delivers faster, though the margin varies.
- **Goal Seek What-If Analysis Impact:** The Goal Seek Analysis shows an optimized order distribution towards FastWheels, reducing both cost and delivery time. For instance, after optimization, 85% of Bangalore-Bangalore orders are assigned to FastWheels, reducing the delivery time to 2 days at an average cost of ₹189.
- **Strategy Recommendation:** The analysis suggests that FastWheels is highly efficient for local routes in terms of both cost and delivery speed. However, for outstation routes, a mixed strategy might be more effective, depending on the route, to balance costs and delivery times effectively.

## Conclusion

Based on the data analysis, FastWheels generally offers lower costs and faster delivery times compared to Ship2Home, especially on local routes. This insight can guide the e-commerce company in making informed decisions about which logistic provider to choose for different routes.
