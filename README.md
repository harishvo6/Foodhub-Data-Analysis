

# FoodHub Data Analysis

## Project Overview
With the growing number of restaurants in New York and the rising reliance on online food delivery by students and busy professionals, **FoodHub**, a food aggregator app, offers seamless access to a variety of restaurants. This project analyzes customer order data from the FoodHub platform to uncover insights that can improve customer experience, streamline restaurant performance, and optimize delivery operations.

## Objective
As a Data Scientist at FoodHub, you’ve been tasked with analyzing historical order data to answer key business questions. The insights derived will help FoodHub:
- Understand customer preferences.
- Identify top-performing restaurants and cuisines.
- Improve delivery and preparation efficiency.
- Enhance user experience and satisfaction.

## Data Description
The dataset includes detailed information on customer orders placed via the FoodHub app. Each row represents a completed order with the following attributes:

| Column Name           | Description |
|-----------------------|-------------|
| `order_id`            | Unique ID of the order |
| `customer_id`         | Unique ID of the customer |
| `restaurant_name`     | Name of the restaurant fulfilling the order |
| `cuisine_type`        | Type of cuisine ordered |
| `cost`                | Cost of the order in USD |
| `day_of_the_week`     | Whether the order was placed on a weekday or weekend |
| `rating`              | Customer rating for the order (out of 5) |
| `food_preparation_time` | Time (in minutes) taken by the restaurant to prepare the food |
| `delivery_time`       | Time (in minutes) taken by the delivery person to deliver the food |

## Exploratory Data Analysis (EDA)
The analysis covered:
- Order volume trends by weekday vs weekend
- Popular cuisines and top-performing restaurants
- Distribution of delivery and food preparation times
- Customer satisfaction analysis via rating trends
- Relationship between cost, delivery efficiency, and rating

## Key Insights & Recommendations
- High-demand cuisines: Certain cuisines like Italian and Chinese had consistently high order volumes; marketing these more aggressively could improve engagement.
- Delivery bottlenecks: Longer delivery times on weekends suggest a need to scale delivery personnel or optimize routing.
- Restaurant performance: A small percentage of restaurants contributed to a large portion of high-rated orders; consider promoting them in-app.
- Ratings correlation: High preparation and delivery time negatively affected customer satisfaction, especially for orders exceeding 45 minutes total.

## Tech Stack
- Language: Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- Notebook: Jupyter Notebook  
- Visualization: Interactive and static plots

## Project Structure

foodhub-data-analysis/
│
├── data/
│ └── foodhub_orders.csv
│
├── notebooks/
│ └── foodhub_analysis.ipynb
│
├── images/
│ └── (charts used in README or presentation)
│
├── README.md
└── requirements.txt




## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/foodhub-data-analysis.git
   cd foodhub-data-analysis


## Install dependencies:
pip install -r requirements.txt

## Open the notebook:
jupyter notebook notebooks/foodhub_analysis.ipynb



## License
This project is licensed under the MIT License
