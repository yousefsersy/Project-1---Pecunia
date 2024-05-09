# Project-1---Pecunia
**Pecunia** an Application developed by Jill Baker, Yousef Sersy, Josue St. Louis, and Elizabeth Ogando.

**Description**:
Our exchange rate calculator and predictor is designed to provide users with accurate exchange rate calculations and predictions for multiple currencies. By utilizing Python's Pandas library and integrating several APIs, including those for historical exchange rate data, our tool employs sophisticated statistical methods such as standard deviation, percent change analysis, and Monte Carlo simulation to forecast exchange rate movements over the next 6 months to 1 year.

**Features**:
Multi-Currency Support: Our tool supports a range of currencies, allowing users to calculate and predict exchange rates for various currency pairs.
Historical Data Analysis: Leveraging historical exchange rate data from the past 3 years, our tool analyzes trends, patterns, and fluctuations to generate predictive models.

**Standard Deviation Analysis**: By calculating the standard deviation of historical exchange rate fluctuations, our tool assesses the volatility of currency pairs, aiding in forecasting future movements.
Percent Change Analysis: Analyzing the percentage change in exchange rates over time provides valuable insights into currency trends and enables more accurate predictions.

**Monte Carlo Simulation**: Employing Monte Carlo simulation techniques, our tool generates multiple possible future scenarios based on historical data, offering probabilistic forecasts of exchange rate movements.

**Customizable Time Frame**: Users can specify the time frame for predictions, ranging from 6 months to 1 year, based on their requirements.
API Integration: Integration with APIs ensures access to up-to-date exchange rate data and enhances the accuracy of predictions.

**User-Friendly Interface**: The interface is designed to be intuitive and user-friendly, allowing both novice and experienced users to navigate and utilize the tool effectively.

**How It Works**:
Data Retrieval: Historical exchange rate data for the past 3 years is retrieved from APIs.
Data Analysis: The retrieved data is analyzed using statistical methods such as standard deviation and percent change analysis to identify patterns and trends.

**Model Generation**: Based on the analysis, predictive models are generated using Monte Carlo simulation to forecast future exchange rate movements.
Prediction Generation: Users input their desired currency pair and time frame for prediction. The tool generates and presents the predicted exchange rates along with confidence intervals derived from the Monte Carlo simulation.
Output Presentation: Predicted exchange rates are presented to the user in a clear and comprehensible format, facilitating informed decision-making.

**Research Questions**
What is the current exchange rate between Currency A and Currency B?
What is the predicted exchange rate between Currency A and Currency B in 1 year?
How volatile is the exchange rate between Currency A and Currency B?


**Major Findings**

*Current Exchange Rates*: We were able to discover the current exchange rates via an API. In addition, it was a challenge to store/restore the data. We were able to resolve this using the %store function. 

*Predicted Exchange Rate*: By translating the data into visualizations such as histograms and density plots, we were able to learn that the exchange rate in 1 year between USD and the Euro has a 95% chance to land between $0.90-$1.22. 

*Volatility of Historical Exchange Rate*: With the help of some historical data retrieved from NASDAQ, we were able to create a 21-day rolling standard deviation plot which showed us how volatile the exchange rate is between USD and the Euro. We concluded that the volatility changes over time based on economic and political events.


**Tasks**:
Proposal- All
Presentation Slides- Elizabeth Ogando
Data Retrieval and Cleaning- Elizabeth Ogando
Build Form- Jill Baker
Show Historic Data- Yousef Sersy
Show Predictive Analysis- Josue St. Louis
