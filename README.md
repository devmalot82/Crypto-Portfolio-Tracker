# Crypto Portfolio Tracker
A live automatic crypto portfolio tracker in Google Sheets using JavaScript featuring:
- Live portfolio value tracking. 
- Automatic asset data recording for analysis and graphs.
- Recommends worst and best returns on investment.

**[Get the crypto portfolio tracker here!](https://docs.google.com/spreadsheets/d/1saml1DQpLZTZ1_3jYbYv1iWW8v03Vdr-/edit?usp=sharing&ouid=104316393434852743675&rtpof=true&sd=true)** 


**To use all the features of this document a google account is required.*

# What does it do?
The spreadsheet presents the live value of your portfolio and records this information and other information such as share price, % changes, and weights every day for historical records, analysis, and producing graphs. The Portfolio Tracker is automated using javascript written in the Google Sheets script editor (similar to Excel's VBA). Portfolio values are automatically recorded and stored in seperate sheets in the document using time-based triggers. These historical values are used in the 'Portfolio' sheet for periodic change values, and in the 'Summary' sheet for analysis of returns and graphs. 
*The Portfolio Tracker is set up to automatically record values for 8 assets (5 Stocks, 1 Bonds ETF, 1 Commodities ETF, 1 Cash) which can be adjusted to any chosen assets available on Google Finance, to add more assets see below.**
- The 'Portfolio' sheet contains all live information about assets in the portfolio. Once data is initially manually inputted, cells update live - the data is used for the 'Portfolio Breakdown' graphs in the 'Summary' sheet. 
- The 'Summary' sheet contains analysis of portfolio returns and graphs - analysis is manually calculated using formalas and data recorded in other sheets.
- The 'Current Historical Portfolio (Asset Type)' sheet contains automatically recorded historical data of the asset types in the portfolio e.g. stocks, bonds etc. - the data is used for the 'Portfolio Value (Asset Type)' graph in the 'Summary' sheet. 
- The 'Current Historical Portfolio (Per Asset)' sheet contains automatically recorded historical data of the individual assets in the portfolio e.g. Facebook, Apple etc. - the data is used for the 'Portfolio Value (Per Asset)' graph in the 'Summary' sheet. 
- The 'Realised Historical Portfolio (Per Asset)' sheet contains any assets that have previously been automatically recorded in the 'Current Historical Portfolio (Per Asset)' sheet, and are no longer held.
- The 'In-Day Portfolio Change' sheet contains automatically recorded data of the portfolio value throughout the day - the data is used for the 'In-Day Portfolio Change' graph displayed in email alerts.
- Email alerts are automatically sent when the portfolio reaches a certain level (set in the 'Additional Information' section of the 'Portfolio' sheet) of loss/gain in a day, e.g. if % day change is greater than 'Day Gain Alert Level 1', an email alert is sent. There are 2 types of email alerts, 'Loss Alerts' and 'Gain Alerts'; email alerts feature information about 'Day Change (%)' and key insights on portfolio changes over week, month and total periods.
