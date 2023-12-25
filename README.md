# Exploring Influential Factors: Understanding US Home Price Trends Over 20 Years

The project aims to analyze the impact of key economic and housing market factors on US home prices over the last two decades using the S&P Case-Shiller Home Price Index as a proxy. This study will encompass six major steps. 

- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation

## Analysis Results
Model Performance
![image](https://github.com/grzzlyb/home-price-trends/assets/123747958/0b99f852-b07f-4a69-8f02-bff36afe0fd9)

Feature Performance
![image](https://github.com/grzzlyb/home-price-trends/assets/123747958/daa5900a-2dd8-46b1-97c1-be342344508e)

The above result highlights that areas with more people tend to have higher home prices. It suggests **population** changes strongly impact how home prices move. However, while population stands out, it's just one part of the picture. Other factors like income, GDP, etc also play roles in determining home prices.

Also, when **house_st** reflecting the count of new housing projects started, has less importance in predicting home prices, it implies that the number of new housing initiatives might not strongly influence or forecast changes in home prices as per this model. Essentially, this suggests that in the context of predicting home prices, the quantity of new housing projects commenced doesn't seem to be a major driving factor based on this analysis.

## Tools and Technologies Used
- Python, Pandas, NumPy, Scikit-learn for data processing and modeling.
- Data has been gathered from [https://fred.stlouisfed.org/](url)

## Usage
1. Clone the repository.
2. Install necessary dependencies.
3. Run the notebook/script for comprehensive analysis.

Feel free to contribute or provide feedback!
