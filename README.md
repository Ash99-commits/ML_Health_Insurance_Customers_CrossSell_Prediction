# ML Health Insurance Customers CrossSell Prediction

Overview
--------

This project builds a predictive model to help an insurance company cross-sell Vehicle Insurance to existing Health Insurance customers. Using demographics, vehicle info, and policy data, it identifies likely buyers through EDA, feature engineering, and machine learning to boost marketing efficiency.

Project Summary
---------------
A structured process is followed:

* Exploratory Data Analysis (EDA): To extract meaningful insights about customer behavior and product engagement.
* Feature Engineering: To enhance and refine data for optimal predictive power.
* Model Development & Validation: To build a reliable predictive analytics solution for business use.

Upon deployment, the solution is expected to optimize marketing efficiency, enabling the client to reach the right customers with the right offer at the right time. This not only reduces acquisition costs but also enhances customer experience and contributes to higher revenue growth through improved conversion rates.

Ultimately, this project delivers a scalable, data-driven decision-support system that empowers the insurance company to make informed, targeted, and impactful marketing decisions for its Vehicle Insurance expansion strategy.

Dataset Features/Columns Description
------------------------------------

**id:** Identifier for each customer.
**Gender:** Gender of the policyholder.
**Age:** Age of the policyholder.
**Driving_License:** Indicates whether the policyholder has a driving license (1 for yes, 0 for no).
**Region_Code:** Coded representation of the region of the policyholder.
**Previously_Insured:** Indicates whether the policyholder already has vehicle insurance (1 for yes, 0 for no).
**Vehicle_Age:** Age of the vehicle.
**Vehicle_Damage:** Indicates whether the vehicle was previously damaged (Yes or No).
**Annual_Premium:** The amount of premium paid annually by the policyholder.
**Policy_Sales_Channel:** Code for the channel of outreach to the policyholder.
**Vintage:** Number of days the policyholder has been associated with the company.
**Response:** Target variable indicating whether the policyholder is interested in vehicle insurance (1 for interested, 0 for not interested).

Methodology
-----------

### Data Analysis
* Exploratory Data Analysis (EDA): Performed an in-depth EDA to uncover insights about customer demographics, vehicle characteristics, and insurance policy details.
* Data Splitting, Feature Scaling and Handling Imbalaces were performed to Optimize and transform the dataset enhancing the effectiveness of predictive modeling.

### ML Model Building
* Employed a set of 6 well-established machine learning algorithms known for their reliability and effectiveness in such scenarios.
* This allowed us to compare performances across linear, tree-based, and ensemble approaches.

### Outcomes
* Pattern Recognition: Discovered significant patterns and relationships influencing a customer’s likelihood to purchase Vehicle Insurance.
* Strategic Insights: Delivered actionable insights to guide the insurance company’s marketing strategies.
* Business Impact: The model’s implementation is expected to improve targeting efficiency and increase conversion rates, positively impacting revenue.

ML Models Used for Classification :-
-----------------------------------
1. Logistic Regression
2. Gaussian Naive Bayes
3. Random Forest
4. Decision Trees
5. Gradient Boosting Machines
6. XGBoost

Conclusion
----------
This ML project successfully built, evaluated, and optimized multiple models to predict customer interest in vehicle insurance. Through careful preprocessing, model selection, and performance evaluation, we identified the best models aligned with different business objectives. The finalized model demonstrates strong predictive performance and reliability, as verified against the test set. With the model now validated and saved, it is ready to be deployed for real-world marketing campaigns.
