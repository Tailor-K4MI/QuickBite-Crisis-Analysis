# QuickBite Crisis Analysis
  This project is based on the 18th resume project challenge by codebasics and aims to provide insights for crisis recovery in an online food delivery startup "QuickBite".
## Project Overview
QuickBite Express is an exploratory data analysis (EDA) project focused on understanding the performance, customer behavior, and operational efficiency of the QuickBite food delivery platform. The project analyzes data covering customer orders, restaurant activity, delivery performance, ratings, and customer sentiments to identify critical trends and issues during a crisis period in 2025.

## Objective
The primary objectives of this project are to:
- Quantify the impact of a crisis period (June-September 2025) on order volumes, cancellations, delivery times, and revenue.
- Identify the cities and restaurants most affected by the order and revenue decline.
- Evaluate changes in customer loyalty and satisfaction via order frequency and ratings analysis.
- Extract insights from customer reviews to understand negative sentiment drivers.
- Provide actionable recommendations to improve delivery service levels, customer experience, and revenue recovery.
  
For more details refer to the `Primary and Secondary Analysis.pdf`.

## Dataset Description
The analysis uses the QuickBite Express database containing multiple tables:
- **factorders**: Customer order details, timestamps, order amounts, cancellations, and payment types.
- **factorderitems**: Items included in each order with prices.
- **ratings**: Customer ratings and reviews linked to orders.
- **deliveryperformance**: Delivery times, delays, miles traveled, and SLA compliance.
- **customeronboard**: Customer profile details and onboarding timestamps.
- **restaurant**: Restaurant locations and categories.
- **deliverypartner**: Delivery partner profiles including vehicle type and work status.
- **menu**: Menu items and pricing.

These detailed datasets were used to capture multiple dimensions of platform performance over time.

## Key Problem Statements & Insights
- **Order Decline:** Orders fell by approximately 69% during the crisis period (Jun-Sep 2025).
- **Cities Affected:** Chennai, Bengaluru, Kolkata, Hyderabad, and Ahmedabad experienced the steepest decline.
- **Cancellation Rates:** Cancellation rate nearly doubled from 6.06% to 11.91% during the crisis.
- **Delivery SLA:** Average delivery time increased from 39.52 to 60.14 minutes; SLA compliance dropped sharply.
- **Customer Ratings:** Customer ratings declined significantly, with sharp drops in June and April 2025.
- **Negative Sentiments:** Common negative review keywords were "issue," "late," "cold," "poor," and "bad."
- **Revenue Impact:** Revenue dropped by over ₹26.5 million during the crisis.
- **Customer Loyalty:** Almost half of the frequent pre-crisis customers stopped ordering during the crisis.
- **High-Value Customers:** Spending and rating declines affected key urban centers and popular cuisines.

## Tools & Technologies
- Python (Pandas, NumPy, NLTK)
- Jupyter Notebook for data cleaning, exploration.
- Text analysis for sentiment extraction from customer reviews
- PowerBI for visualization

## How to Run the Analysis
1. Clone this repository.
2. Ensure Python with required libraries (pandas, numpy, nltk) is installed.
3. Load the datasets into the environment.
4. Open the `QuickBite.ipynb` notebook.
5. Follow the notebook cells sequentially for data cleaning, transformation, analysis.
6. Open the `QuickBite.pbix` file for the visualization.
7. Review outputs and insights documented in the notebook cells.

## Conclusion
This EDA project offers a comprehensive view into how the QuickBite platform was impacted by the crisis period of 2025, showcasing key business challenges in order volumes, customer retention, delivery service, and revenue. The insights equip stakeholders with data-driven evidence to strategize recovery and improve customer experience.

## License
This project is for educational and demonstration purposes.

---

*For detailed tables, code implementations, and visualizations, please refer to the Jupyter notebook file and powerbi report included in this repository.*
