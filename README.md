# Exploring Influential Factors: Understanding US Home Price Trends Over 20 Years

The project aims to analyze the impact of key economic and housing market factors on US home prices over the last two decades using the S&P Case-Shiller Home Price Index as a proxy. This study will encompass six major steps. 

- Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Model Evaluation

## Analysis Results
| ![image](https://github.com/grzzlyb/home-price-trends/assets/123747958/0b99f852-b07f-4a69-8f02-bff36afe0fd9) |
|:--:|
| *Model Performance* |

| Features       | Corr  |
| ------------- | -----:|
| MSPUS         |0.980144|
|PPI_Cement      |0.964074|
|GDP                     |0.960633|
|income                  |0.955608|
|PPI_Concrete            |0.939072|
|population              |0.896974|
|total_emp_cons          |0.812130|
|new_private_hw_under    |0.634935|
|all_Const_Emp           |0.560479|
|home_ow_rate            |0.207294|
|monthly_supply          |0.169504|
|permit                  |0.127189|
|house_st               |-0.001742|
|new_private_house      |-0.068468|
|unemployed_rate        |-0.249211|
|IPI_Cement             |-0.260807|
|p_saving_rate          |-0.286001|
|emratio                |-0.538776|
|mortgage_rate          |-0.730709|
|labor_percent          |-0.788313|

| ![image](https://github.com/grzzlyb/home-price-trends/assets/123747958/daa5900a-2dd8-46b1-97c1-be342344508e)|
|:--:|
| *Feature Importance* |

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
