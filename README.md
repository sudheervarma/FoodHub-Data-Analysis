# FoodHub Data Analysis

## 📖 Context  
The number of restaurants in New York is increasing rapidly. With busy lifestyles, students and professionals heavily rely on these restaurants for their daily meals. Online food delivery services provide a convenient solution by bringing food from favorite restaurants directly to customers’ doors.  

**FoodHub** is one such food aggregator platform that connects multiple restaurants to customers through a single app.  
The process works as follows:  
1. Customers place an order through the FoodHub app.  
2. The restaurant confirms the order.  
3. A delivery person is assigned to pick up the order.  
4. Once the food is ready, the delivery person collects it and delivers it to the customer.  
5. Customers can rate the order after completion.  
6. FoodHub earns revenue by charging a fixed margin from each order placed.  

---

## 🎯 Objective  
FoodHub has stored detailed information about all orders placed through its platform. As a **Data Scientist**, your task is to analyze this data and answer key business questions to:  
- Understand customer demand trends.  
- Identify high-performing restaurants and cuisines.  
- Improve delivery efficiency and customer experience.  

---

## 📊 Dataset Description  

The dataset contains records of food orders, including details about customers, restaurants, preparation, delivery, and ratings.  

### Data Dictionary  

| Column Name            | Description |
|-------------------------|-------------|
| **order_id**           | Unique ID of the order |
| **customer_id**        | ID of the customer who placed the order |
| **restaurant_name**    | Name of the restaurant |
| **cuisine_type**       | Type of cuisine ordered |
| **cost_of_the_order**  | Total cost of the order |
| **day_of_the_week**    | Indicates if the order was placed on a **weekday** (Mon–Fri) or **weekend** (Sat–Sun) |
| **rating**             | Rating given by the customer (out of 5) |
| **food_preparation_time** | Time (in minutes) taken by the restaurant to prepare the food (difference between order confirmation and pick-up confirmation) |
| **delivery_time**      | Time (in minutes) taken by the delivery person to deliver the food (difference between pick-up and drop-off) |

---

## 🛠️ Tech Stack  
- **Language:** Python  
- **Libraries:**  
  - pandas (data manipulation)  
  - numpy (numerical computations)  
  - matplotlib / seaborn (data visualization)  
  - jupyter notebook (analysis & reporting)  

---

## 🚀 Project Workflow  
1. **Data Loading & Exploration**  
   - Import dataset  
   - Explore data structure, check missing values, data types  

2. **Data Cleaning & Preparation**  
   - Handle missing/null values  
   - Convert columns to correct data types  
   - Perform necessary transformations  

3. **Exploratory Data Analysis (EDA)**  
   - Analyze order trends across weekdays vs weekends  
   - Explore distribution of ratings, costs, and delivery times  
   - Identify top restaurants and cuisines  
   - Check relationship between preparation time, delivery time, and ratings  

4. **Insights & Business Recommendations**  
   - Highlight restaurants/cuisines with high demand  
   - Identify bottlenecks in food preparation or delivery  
   - Recommend strategies to improve ratings and customer satisfaction  

---

## 📌 Sample Analysis Questions (KPIs)  

Here are some example questions the **FoodHub Data Science team** might want answered:  

1. **Customer Demand & Order Trends**  
   - Which days (weekdays vs weekends) have the highest order volumes?  
   - What are the peak hours for order placements?  

2. **Restaurant Performance**  
   - Which restaurants receive the highest number of orders?  
   - Which cuisines are the most popular among customers?  
   - Which restaurants consistently receive high customer ratings?  

3. **Revenue Insights**  
   - What is the average cost of an order?  
   - Which restaurant generates the highest revenue?  
   - Are high-cost orders associated with higher or lower ratings?  

4. **Delivery & Operational Efficiency**  
   - What is the average food preparation time across restaurants?  
   - What is the average delivery time across locations?  
   - Does longer preparation/delivery time impact customer ratings?  

5. **Customer Experience**  
   - What percentage of orders receive a rating of 5 (excellent service)?  
   - Which factors (cost, cuisine, day of week, prep/delivery time) influence ratings the most?  

---

## 📊 Conclusions  

The analysis of the FoodHub dataset provides key insights into customer behavior, restaurant performance, and operational efficiency.  

### Customer Preferences & Demand Trends  
- **Shake Shack** is the most popular restaurant with **219 orders**, reflecting strong customer preference.  
- **American cuisine** is the most ordered, followed by **Japanese** and **Italian**, indicating high demand for these cuisines.  
- Order volumes **peak on weekends**, highlighting a key opportunity for strategic promotions.  

### Financial Insights  
- The **average order cost** is **$16.50**, with a notable percentage exceeding $20.  
- The company generates **$6,166.30 in total revenue**, suggesting a strong revenue stream.  

### Delivery & Operational Performance  
- The **mean delivery time** is **24.16 minutes**, though a small fraction of orders exceed 60 minutes, potentially impacting customer satisfaction.  
- **Weekday deliveries** tend to take slightly longer than weekends, possibly due to traffic conditions or higher order volume.  
- Opportunities exist to enhance **food preparation and delivery efficiency**, reducing wait times for customers.  

### Customer Satisfaction & Ratings  
- Most customers are satisfied, as shown by a high number of **5-star ratings**.  
- A significant number of orders are **not rated**, presenting an opportunity to boost customer engagement and feedback collection.  
- **Longer delivery times** are associated with **lower ratings**, emphasizing the need for timely service.  
- **Higher-cost orders** tend to receive better ratings, suggesting a correlation between price and customer satisfaction.  

### Strategic Opportunities  
- Certain restaurants meet the criteria for **promotional offers** based on their ratings and order volume, offering a marketing advantage.  
- **Weekend orders** tend to have higher average costs, indicating an opportunity for **targeted promotions** during peak demand.  
- Some cuisines consistently receive higher ratings, which could inform **menu expansion or targeted advertising**.  

FoodHub's data-driven insights reveal **high revenue potential, strong weekend demand, and customer satisfaction trends**. By enhancing delivery efficiency, leveraging high-rated restaurants for promotions, and improving customer engagement, the company can further optimize its operations and maximize revenue.  

---

## 💡 Recommendations  

Based on the analysis of FoodHub’s operations and customer behavior, we propose the following strategic recommendations to enhance growth, efficiency, and customer satisfaction:  

### Marketing & Customer Engagement  
- **Promote Popular Restaurants & Cuisines:** Focus marketing efforts on high-demand restaurants (e.g., Shake Shack) and top cuisines (American, Japanese, Italian).  
- **Targeted Weekend Promotions:** Implement discounts or exclusive deals on weekends, when order volumes are highest.  
- **Leverage Social Media & Influencer Marketing:** Promote top-rated restaurants and limited-time offers through social channels.  
- **Implement Loyalty Programs:** Introduce rewards or subscription-based discounts to encourage repeat orders.  

### Operational Efficiency & Delivery Optimization  
- **Reduce Delivery Bottlenecks:** Identify factors causing longer delivery times (especially weekdays) and optimize routes/restaurant prep times.  
- **Implement Real-Time Tracking & Notifications:** Keep customers informed about delays via app notifications.  
- **Analyze Outliers in Delivery Times:** Investigate orders exceeding 60 minutes to pinpoint inefficiencies.  

### Data-Driven Business Growth  
- **Customer Segmentation:** Use analytics to group customers by behavior and target them with personalized offers.  
- **Evaluate Pricing Strategies:** Analyze order cost trends and optimize promotions.  
- **Expand Partnerships:** Add new restaurants with high-rated cuisines to diversify offerings.  

### Customer Satisfaction & Feedback Utilization  
- **Encourage Reviews & Ratings:** Offer incentives for customers to leave feedback.  
- **Monitor Satisfaction Trends:** Regularly track ratings, reviews, and complaints.  
- **Improve Service Based on Feedback:** Refine ordering, delivery, and food quality from customer insights.  

### Strategic Growth & Expansion  
- **Evaluate Seasonal Demand:** Identify peak seasons for promotions.  
- **Expand Delivery Zones:** Grow into new geographic areas.  
- **Monitor Competitors:** Adapt to industry trends and competitor pricing models.  

By implementing these strategies, FoodHub can **optimize operations, improve retention, and maximize profitability**.  

---

## 📂 Repository Structure  
````
📦 FoodHub-Data-Analysis
├── 📁 data
│   └── foodhub_orders.csv
├── 📁 notebooks
│   └── FoodHub_Project_Notebook_Code.ipynb
├── 📁 scripts
│   └── data_cleaning.py
│   └── eda.py
├── 📄 README.md
└── 📄 requirements.txt
`````
---

## 📌 Future Improvements  
- Build a predictive model to estimate delivery times.  
- Use machine learning to predict customer ratings based on order details.  
- Deploy dashboards for real-time tracking of orders and performance.  

---

## 🤝 Contributing  
Contributions are welcome! Please fork the repo, make changes, and submit a pull request.  

---

## 📜 License  
This project is licensed under the MIT License.  
