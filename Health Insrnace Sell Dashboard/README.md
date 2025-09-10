## Health Insurance Cross-Sell Dashboard

This project is a Power BI dashboard that analyzes customer behavior in purchasing vehicle insurance, given their existing health insurance status. It explores demographic factors, vehicle-related attributes, premium levels, and sales channels to uncover what drives cross-sell opportunities.

## Project Files

- `train.xlsx` – Raw dataset of 381,109 insurance customer records
- `Health Insurance Cross Sale Dashboard.pbix` – Power BI report file (created in Power BI Desktop)
- `Health Insurance Cross Sale Dashboard.pdf` – Exported dashboard

## Dashboard Highlights

### Key KPIs
- **Number of Records:** 381K
- **Purchase Rate:** 12.3% overall conversion
- **Cross-Sell Rate:** 0.46% (health-insured customers also buying vehicle insurance)
- **Average Premium:** 31K
- **Total Premium:** 12B

### Demographics & Customer Behavior
- **Response Rate by Age:** Younger customers are less likely to buy, while middle-aged groups show higher uptake.
- **Gender:** Males (13.8%) purchase more frequently than females (10.4%).

### Vehicle & Premium Insights
- **Response Rate by Vehicle Age:** Older vehicles (>2 years) have the highest purchase rate (~29.4%).
- **Vehicle Damage:** Customers with previously damaged vehicles are significantly more likely to buy (~23.8%).
- **Response Rate by Premium Group:** Uptake increases with higher premium ranges, peaking above 80K.

### Sales Channel Performance
- **Top 10 Sales Channels:** Dashboard highlights the highest-performing channels by conversion rate.
- **Vintage Effect:** Longer customer relationships correlate with slightly higher conversion rates.

## Dataset Source

This dataset comes from Kaggle: [Health Insurance Cross Sell Prediction](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction).  
It contains customer demographic, insurance, and vehicle-related attributes used to predict whether a customer will purchase vehicle insurance.

## Variable Description

| Variable              | Definition                                                                 |
|-----------------------|----------------------------------------------------------------------------|
| id                    | Unique ID for the customer                                                |
| Gender                | Gender of the customer                                                    |
| Age                   | Age of the customer                                                       |
| Driving_License       | 0: Customer does not have a driving license, 1: Customer already has one   |
| Region_Code           | Unique code for the region of the customer                                |
| Previously_Insured    | 1: Customer already has vehicle insurance, 0: Customer does not           |
| Vehicle_Age           | Age of the vehicle                                                        |
| Vehicle_Damage        | 1: Customer’s vehicle was previously damaged, 0: No damage in the past    |
| Annual_Premium        | Amount the customer needs to pay as premium per year                      |
| Policy_Sales_Channel  | Anonymized code for outreach channel (agents, email, phone, in-person, etc.) |
| Vintage               | Number of days the customer has been associated with the company          |
| Response              | 1: Customer is interested (purchased vehicle insurance), 0: Not interested |


## How to Use

1. Download the `.pbix` file from this folder.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Interact with filters (e.g., Gender, Vehicle Damage, Premium Group) to explore customer patterns.
4. Use insights to identify key customer segments for cross-selling opportunities.

## Contact

If you have any questions, suggestions, or would like to collaborate:

- 📧 Email: [your.email@example.com](mailto:your.email@example.com)  
- 💼 LinkedIn: [https://www.linkedin.com/in/yourprofile](https://www.linkedin.com/in/yourprofile)  
