# Clean Energy Stock Investment Analysis

We have helped Steve to analyze the solar energy stock tickers so he can help his parent. At the begining we create a macro that can run through 2017 and 2018 stock data and find the rate of return for each ticker. Eventhough the macro ran well but it seems to take litle time to run (3000 data each year).  Steve told us that he can use the macro to run even more data ( for example > 10,000 data) and suggest we need to make macro run faster and here are the results :

#### 2017 Stock Rate of Return:
   After modify the macro , the run time improve from  0.8 second to 0.1 second  : https://github.com/ttan0408/stock-analysis/blob/main/VBA_Challenge_2017.PNG
   
   In 2017, most of the solar company stock have positive return with an average of 67% return over 12 company tickers. The highest return is DQ with 199% return but              supprisingly it has the lowest daily trading volume compare to others
   
   TERP is the only company has the negative return eventhough 2017 seems to be a good year for solar energy stock market.
   
   All the statistical summary of 2017 12 stocks analysis are here :  https://github.com/ttan0408/stock-analysis/blob/main/VBA_Challenge_2017_Return.PNG

#### 2018 Stock Rate of Return:

  2018 is the bad year for the solar energy market, since most of the company has negative return with DQ and JKS are the worse in the 12 stock tickers
  
  Interesting, eventhough 2018 is the bad year but ENPH and RUN made it through impressive positive return of 80% with also highest trading volume in 2018
  
  Macro analysis run time for 2018 iis also improve from 0.8 second to 0.1 second after refactoring the VBA code.
  
  All the summary and run time speed are list as below 
  
  
  
