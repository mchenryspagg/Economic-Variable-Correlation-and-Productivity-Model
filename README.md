# ECONOMIC VARIABLE CORRELATION AND PRODUCTIVITY MODEL

## Table of contents
- [About](#about)
- [Objective](#objective)
- [Project Overview](#project-overview)
  - [Objective](#objective)
  - [Steps](#steps)
  - [Deliverables](#deliverables)
- [Data Collection](#data-collection)
- [Links](#links)
- [Data Charts](#data-charts)
- [Analysis and Correlation](#analysis-and-correlation)
  - [Theoretical framework](#theoretical-framework)
- [Productivity Model](#productivity-model)
  - [Productivity Baseline](#productivity-baseline)
- [Recommendations](#recommendations)
- [Acknowledgements](#acknowledgements)


## About
The study's main purpose is to analyze the correlation between key economic variables (M1 money supply, real exchange rate, stock market performance, and inflation rate) and their impact on Nigeria’s economic productivity from 2014 to 2024. 
This study would attempt to uncover trends, challenges, and opportunities, providing valuable insights for policymakers, investors, and stakeholders


## Project Overview

### Objective
To conduct a financial analysis involving the correlation between key economic variables and identifying undervalued companies using financial data.

### Steps:

1. **Data Collection:**
   - Gather data for M1 money supply, real exchange rate (black market), country stock market performance, and inflation rate for Nigeria and the USA.
   - Ensure data covers a sufficient time span to analyze trends and correlations.

2. **Theoretical Framework:**
   - Theorize that increased money supply leads to currency depreciation, stock market appreciation, and increased inflation due to a baseline productivity level.

3. **Productivity Baseline:**
   - Determine an appropriate formula for calculating the productivity baseline.
   - Example: If money supply is flat but productivity increases, the exchange rate should rise, and inflation should decrease.

4. **Productivity Model:**
   - Develop a model combining the three variables to calculate productivity.
   - Analyze if productivity appears flat, decreasing slightly, or increasing.

5. **Correlation Analysis:**
   - Plot the variables on a chart to visualize their relationships.
   - Analyze the correlations between the variables, considering potential time-shifted correlations.
   - Discuss the observed correlations and their implications.

6. **Currency Devaluation:**
   - Calculate real currency devaluation using a reference currency with flat M1 growth and stable productivity.

### Deliverables:
-	**Data Charts**: Visual representation of the economic variables and their correlations.
-	**Analysis Report**: Detailed discussion of the correlations and theoretical implications.
-	**Productivity Model**: Model showing the calculated productivity for Nigeria.
-	**Presentation**: Summarize findings and present the theoretical framework, data analysis, and productivity model.


## Data Collection
Extensive data spanning the last 10 years (2014 - 2024) was gathered for:

- [M1 money supply](https://github.com/mchenryspagg/Economic-Variable-Correlation-and-Productivity-Model/blob/main/NG%20M1%20Money%20Supply.xlsx), 
- [real exchange rate](https://github.com/mchenryspagg/Economic-Variable-Correlation-and-Productivity-Model/blob/main/NG%20Exchange%20rates.xlsx),
- [stock market performance index](https://github.com/mchenryspagg/Economic-Variable-Correlation-and-Productivity-Model/blob/main/NG%20Stock%20Market%20Index.xlsx), and
- [inflation rate](https://github.com/mchenryspagg/Economic-Variable-Correlation-and-Productivity-Model/blob/main/NG%20Export%20Inflation%20Rates.xlsx) for Nigeria


## Links
- Detailed slide Presentation showing findings, theoretical framework, analysis, and productivity model - [Link](https://drive.google.com/file/u/0/d/1S4Uo--Y-GeO9YAUcHcMOh7b1GthnP0Cs/view)
- Jupyter Notebook showing the Python codes utilized in building regression models, analysis, and visualizations - [Link](https://github.com/mchenryspagg/Economic-Variable-Correlation-and-Productivity-Model/blob/main/Task%205a%20-%20HNG.ipynb)


## Data Charts
- Nigerian Inflation Rate (2014-2024)

![image](https://github.com/user-attachments/assets/e9390385-e8fe-4450-b543-63ded06d8c96)

- M1 Money Supply (2014-2024)

![image](https://github.com/user-attachments/assets/4ba291b8-2f37-4aa4-9255-c2cf2105aa4d)

- NGN-USD Exchange Rate (2014-2024)

![image](https://github.com/user-attachments/assets/87fa7ca2-5779-42bc-b4ab-9a46b4cd795a)

- Stock Market Index Performance (2014-2024)

![image](https://github.com/user-attachments/assets/2f8fd3eb-b92f-48c7-ab3a-a73053480ef4)


## Analysis and Correlation

The analysis reveals the following relationships:

- **Exchange Rate and Inflation**: Positive correlation; as the Naira depreciates, inflation rises due to higher import costs.
- **Money Supply and Inflation**: Positive correlation; increased money supply leads to higher inflation, driven by increased demand.
- **Stock Market Performance and Inflation**: Mixed relationship; influenced by investor sentiment and economic policies.
- **Money Supply and Stock Market**: Positive correlation; higher money supply boosts stock prices due to increased market liquidity.
  
![image](https://github.com/user-attachments/assets/3367d285-2688-405e-8956-15e87878984c)

These insights underscore the interconnectedness of monetary policy, exchange rates, and economic performance, aiding informed financial and investment decisions.

### Theoretical framework

- **Increased Money Supply**: Central banks increase the money supply through methods like lowering interest rates and purchasing government securities.
- **Currency Depreciation**: More money in circulation reduces currency value, making imports more expensive and exports cheaper.
- **Stock Market Appreciation**: Increased money supply leads to more investment in stocks, raising stock prices.
- **Increased Inflation**: More money in the economy boosts demand for goods and services, leading to higher prices if productivity remains constant.
  
![image](https://github.com/user-attachments/assets/756741d4-1c1a-48b8-9ca1-f730eb0cee38)


## Productivity Model
In other to calculate productivity as a function of the three variables

Productivity = Exchange Rate (USD) x  Stock Market % Change  /  Inflation Rate

![image](https://github.com/user-attachments/assets/7b04fc0a-21f1-488f-a427-0fd4160035dd)

The chart "Productivity Trend Over Time" shows that productivity has remained relatively flat with some fluctuations over the years. 
While there are peaks and troughs, there is no clear long-term trend. However, there is a significant spike at the end of the graph, indicating a sharp increase in productivity around 2024.


## Productivity Baseline
The Productivity Baseline (PB) can be inferred from the relationship between money supply, inflation, and exchange rate and can be 
calculated using the formula:

PB = Money Supply (M1)/ Inflation Rate × Exchange Rate (USD)

This formula assumes that increased productivity results in a higher money supply, lower inflation, and a stronger exchange rate.


## Recommendations
Given the analysis of productivity and the correlation between all four variables, here are some possible recommendations for Nigeria as a country and it's government:

1. **Monitor and Manage Exchange Rates**:
   - Implement policies to stabilize the Naira to mitigate inflation caused by currency depreciation.
   - Encourage export-oriented industries to take advantage of a weaker Naira, potentially balancing the trade deficit.

2. **Control Money Supply**:
   - Regulate the money supply to prevent excessive inflation. This could involve tightening monetary policy when inflationary pressures are high.
   - Promote financial literacy to help the public understand the impact of money supply on inflation and purchasing power.

3. **Stock Market Strategies**:
   - Encourage investment in the stock market by maintaining a stable economic environment and transparent policies.
   - Monitor investor sentiment and economic policies closely to understand their impact on stock market performance.

4. **Inflation Management**:
   - Implement measures to control inflation, such as adjusting interest rates and using fiscal policies to manage demand.
   - Focus on increasing productivity to counteract inflationary pressures, ensuring that supply meets demand.

5. **Enhance Data Analysis and Forecasting**:
   - Use advanced data analytics to predict trends in money supply, exchange rates, and inflation.
   - Develop models to forecast the impact of different economic policies on these variables, aiding in proactive decision-making.

By addressing these areas, Nigeria can better manage the interconnectedness of monetary policy, exchange rates, and economic performance, leading to more informed financial and investment decisions.


## Acknowledgements
This project is part of the project requirements necessary to graduate from Stage 5 at HNG 11 internship for the Data Analyst Track. 
Special appreciation to the organizers of the [HNG internship](https://hng.tech/internship), and to my esteemed team members in the data analyst track.
