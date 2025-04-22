# 🛒 Nature's Basket: Behavioural Analysis – Refining Customer Satisfaction

## 📌 Project Overview  
Nature's Basket is a modern grocery delivery service offering fresh fruits, vegetables, snacks, and drinks to customers across Mumbai. Committed to quality and convenience, the company strives to deliver a seamless shopping experience.

To improve service and customer satisfaction, Nature's Basket has identified order cancellations as a critical area to address. This project focuses on analyzing order data to understand the root causes of cancellations and identify trends among top customers. The insights from this project aim to enhance customer experience, reduce cancellations, and foster long-term loyalty.This project analyzes top customer behavior for Natur's Basket as of **January 1, 2024**, using **RFM (Recency, Frequency, Monetary)** segmentation. It aims to enhance customer satisfaction through dynamic dashboards, personalized feedback analysis, and targeted messaging.

---

## 🗂️ Database Info  
The analysis is based on the following dataset:

- 📁 **[Order Data Sheet]([https://github.com/rashi12121/Nature-s-Basket-Behavioural-Analysis-Refining-Customer-Satisfaction/blob/main/Nature'sBasket_Data.csv])**: Raw data of online orders placed by top customers over the past year. Includes customer details, delivery statuses, and cancellation reasons.

All analysis was performed using **Google Sheets**.

---

## ❓ Questions to Answer

1. What are the main reasons for order cancellations at each dark store?
2. Which dark stores are facing the highest number of cancellations?
3. How are cancellation trends distributed across product categories?
4. Can we segment customers based on their order patterns and delivery statuses?
5. Which customers had their last order or recent orders consecutively canceled?
6. How can Nature’s Basket personalize messages to retain such customers?

---

## 🔍 Exploratory Data Analysis (EDA)

- Cleaned and structured order data for analysis.
- Identified top reasons for cancellations.
- Analyzed order trends across different dark stores and product categories.
- Segmented customers based on their last five orders.
- Highlighted customers with cancellation-heavy order histories.

---

## 📊 Visualization

- Bar charts showing cancellation counts by dark store and reason.
- Pie charts for order status distributions.
- Conditional formatting for identifying customers with repeated cancellations.
- Segmentation tables based on order history patterns.

🖼️ **Cancellation Dashboard Preview:**  
![Cancellation Dashboard](https://github.com/rashi12121/Nature-s-Basket-Behavioural-Analysis-Refining-Customer-Satisfaction/blob/main/Screenshot%202025-04-16%20221434.png)

- **Customer Segmentation**
  - Calculated Recency (in days), Order Frequency, and Monetary value (Total Order Amount)
  - Applied company-defined thresholds to assign RFM scores
  - Categorized customers into:
    - Top-tier Customers
    - Loyal Customers
    - Potential Loyal Customers
  

- **RFM Score Calculation**
  - Mean, Deviation (50% of mean), Min/Max thresholds for scoring

- **Top Customer Analysis**
  - Dashboard with delivery status of last 5 orders
  - Conditional formatting for cancellations
  - Flags customers with consecutive cancellations
![Customer Segmentation-Top Customer Analysis](https://github.com/rashi12121/Nature-s-Basket-Behavioural-Analysis-Refining-Customer-Satisfaction/blob/main/Customer%20Segmentation%20-Top%20Tier%20Customers.png)
  
- **Customer Feedback Analysis**
  - Feedback trends across each customer category
  - Identifies “Major Issues” based on frequency
  - Highlights customers with consistent complaints
![Customer Feedback Analysis](https://github.com/rashi12121/Nature-s-Basket-Behavioural-Analysis-Refining-Customer-Satisfaction/blob/main/Customer%20Feedback%20Analysis.png)

- **Customized Messaging**
  - Auto-generated personalized messages
  - Targeted at customers with recurring or last-order cancellations
  - Linked to specific issues via dynamic lookup
![Customized Message](https://github.com/rashi12121/Nature-s-Basket-Behavioural-Analysis-Refining-Customer-Satisfaction/blob/main/Customized%20Message.png)
## 💡 Key Insights

- A few dark stores contribute to a majority of order cancellations due to stock unavailability.
- Specific product categories face more cancellations, indicating possible supply chain issues.
- A segment of top customers experienced back-to-back order cancellations, highlighting the need for immediate engagement.
- Personalized offers and communication strategies can be developed using segmentation insights to boost retention.
- Deeper insight into customer behavior
- Enhanced ability to retain high-value customers
- Personalized engagement strategy based on real-time data


---

## 🛠️ Tools Used

-  Google Sheets (Data cleaning, EDA, visualizations)
-  Built-in chart tools for visualization
-  Manual formulas and conditional formatting for segmentation
- Data Validation, Conditional Formatting
- Formulas: `FILTER`, `SORT`, `IF`, `VLOOKUP`, `INDEX MATCH`, `ARRAYFORMULA`
- Dynamic Dropdowns and Linked Reports
