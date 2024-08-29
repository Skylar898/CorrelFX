# CorrelFX
Client: Jerichopaul Santos\
By: _Skylar Phanenhour, Justin Charette, Megan Clinch, Adriana Cote, Stefan Djelmo, Cameron Ewing_\
API Used: https://www.exchangerate-api.com/
***
This project idea is proposed by our client; beginner traders often don't know how to navigate the forex trading market or make proper trades, often resulting in them losing money. The proposed solution was CorrelFX, a beginner friendly trading app that uses simulated currency and encourages making the best possible choices when trading in order to teach user's how to properly trade when it comes to the forex market.
***
## Demo
https://github.com/user-attachments/assets/d402b948-77cf-4235-bb50-1222cc5e5267
***
## Tutorial
![tutorial](https://github.com/user-attachments/assets/bc0b1332-260e-4328-a29f-930fc757556f)
- Basic step by step overview of the application
- Can be toggled at any time for ease of access
- Option to skip the tutorial for experienced users
***
## Popup Hints
![popup-hints](https://github.com/user-attachments/assets/9d70c254-07c6-4550-86e0-16e7e86124b0)\
![popup-hint-example](https://github.com/user-attachments/assets/9b436820-28e5-44c8-8803-3978a80662ad)
- Allows beginner user's to familiarize themselves with any terms or calculations that they may not understand 
***
## Chart Features
Both graphs provide the option to toggle ficonnaci retracement levels to support user's where the price could potentially reverse its direction.
![two-month-chart](https://github.com/user-attachments/assets/614284e6-ee70-43b5-b6ba-d2858ac49241)
- Displays the data from the last 2 months by the day within a candlestick chart

![two-day-chart](https://github.com/user-attachments/assets/783f46e7-0fdc-41f6-8d77-67b03e95cb74)
- Displays the data from the last 2 days by every 5 minutes within a line chart
***
## Trading Pair
![trading-pair](https://github.com/user-attachments/assets/c7b4c34c-b32f-428c-83e7-64cfe2bcbcac)
- Dynamically updates the correlation scores of the currencies based on the API currency value
- Promotes the 4 best trading pairs to choose from
***
## API Values
- The currency data is being fetched from exchangerate-api
- Set to fetch the latest currency data every 5 minutes
***
## Indicators
![indicators](https://github.com/user-attachments/assets/089613b9-3690-4d1f-b521-ab213c092bf4)
- The application performs background calculations that are displayed using visual indicators
- These indicators are used to inform the user when they should and should not perform a trade
   - For example, when 2 or more of the indicators are met, the user is encouraged to make a trade; enabling the buy and sell options
***
## Buy and Sell
- Buy and sell actions are based on the trading pair chosen in step 1
- The currency with the higher correlation score (going up in price) will be chosen to be sold
- The currency with the lower correlation score (going down in price) will be chosen to be bought
- Amount entered will be directly converted to the value of the currency (amount * value)
***
## Request Funds
![request-funds](https://github.com/user-attachments/assets/8410deb0-59a4-498b-a0cf-0fa14bea4391)
- Allows the user to add either $10, $100, or $1000 of USD within their wallet
***
## User Wallet
![user-wallet](https://github.com/user-attachments/assets/af2f9919-0370-4667-8003-280b36c79716)
- Displays the amount of each of the 7 currencies in the wallet
- Everything is based on the USD amount:
 - Total balance is displayed in USD; everything gets converted in the total balance
 - The bought currency will be displayed in that currency's amount
 - The sold currency will be converted and added to the USD's amount
***
## Tech Stack
- AWS (Amazon Web Services)
- JavaScript / React
- MUI (Material UI)
- AnyChart
- Exchangerate-api
- Jira
***
## AWS Tools Used
- AWS Amplify
- Amazon Route 53
- Amazon RDS
- IAM
- AWS Secret Manager
- Amazon API Gateway
- AWS Lambda
- Amazon Cognito
- Amazon CloudWatch
