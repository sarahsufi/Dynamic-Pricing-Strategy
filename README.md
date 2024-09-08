Dynamic Pricing Strategy

Overview

This project explores Dynamic Pricing, a data science application used to adjust prices in real-time based on market conditions, customer behavior, and competitor pricing. The goal is to optimize revenue and profitability by implementing a flexible pricing model.

Use Case
The project focuses on a ride-sharing company that needs to update its fixed-rate pricing model to better match demand fluctuations. By leveraging data science techniques, the company can adjust prices dynamically, increasing them during high-demand periods (e.g., rush hours or events) and lowering them when demand is low.

Approach
Data Collection: Utilizes datasets including:
Historical sales data
Customer purchase patterns
Market demand forecasts
Cost data
Customer segmentation
Real-time market data
Data Analysis: Analyzes historical and real-time data to understand demand patterns and pricing impacts.
Model Implementation: Applies Machine Learning algorithms to predict demand and adjust prices in real-time. Models are trained to:
Increase prices during high demand to balance supply and incentivize drivers.
Decrease prices during low demand to attract more customers.
Evaluation: Assesses the performance of the dynamic pricing strategy based on revenue optimization and customer satisfaction.
Dataset
The project uses a dataset ideal for creating a dynamic pricing strategy. You can download the dataset here for further exploration and experimentation.

A Snippet Of Code Outputs 
![newplot-2](https://github.com/user-attachments/assets/759c13e2-fcf6-491b-b12d-4bb4c7b5e7d2)
![newplot-4](https://github.com/user-attachments/assets/5c792533-72ca-4938-8ea8-e535d6095c16)
![newplot-6](https://github.com/user-attachments/assets/90c49b37-16a4-42a5-a18d-6188e09abe52)




Libraries Used
Pandas, Numpy: Data manipulation and analysis
Scikit-Learn: Machine learning algorithms
Matplotlib, Seaborn: Data visualization
Usage

Train Model: Run python train_model.py to train the dynamic pricing model.
Predict Prices: Use python predict_prices.py to apply the model for real-time pricing adjustments.

Author: Sarah Sufi

GitHub: sarahsufi
