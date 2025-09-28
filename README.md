# Research-Fall25

Core Question: How do changes in policy interest rates(Federal Funds Rate) and market rates(Prime Rate) affect US households’ revolving consumer credit balance and credit card delinquency rates over short, medium, and longer horizons?

Sub-questions
Do interest rate increases reduce outstanding credit card balances(debt service channel) or increase them(liquidity constraint channel)?
Do higher interest rates lead to higher delinquency and charge-off rates, and if so, with what lag?
Which rate measure (policy rate vs. market rates) transmits faster to consumer borrowing behavior?
Has the interest rate-consumer credit relationship changed after structural breaks?, such as Global Financial Crisis in 2008 or COVID-19 pandemic?
Are the effects heterogeneous across group (low-income vs. high-income households, if microdata is available?)
Can ML models improve out-of-sample prediction of future revolving credit growth and delinquency, and which features (interest rates, unemployment, income, past credit behavior) drive those predictions?

Data Sources
Interest Rates
Federal Funds Rate (FEDFUNDS)
Bank Prime Loan Rate (DPRIME)
30-Year Mortgage Rate (MORTGAGE30US)
Consumer Credit
Revolving Consumer Credit Outstanding (REVOLCRED)
Total Consumer Credit Outstanding (TOTALSL)
Credit Card Delinquency Rate on Consumer Loans (DRCCLACBS)
Credit Card Charge-Off Rate (CORCCACBS)
Household Debt and Credit (NY Fed) 
Controls 
Unemployment Rate (UNRATE)
CPI All Urban Consumers (CPIAUCSL) or Core CPI
Real Disposable Personal Income (DSPIC96)

Testable Hypotheses
A one percentage point increase in the policy rate reduces revolving credit balances within 3-6 months.
Higher rates increase delinquency and charge-off rates, especially among lower-income households.
Market rates transmit more quickly to consumer credit outcomes than policy rates
