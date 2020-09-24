# Pairs-Trading-Pfizer-and-Merck
The inspiration for this is from the Motley Fool (https://www.fool.com/investing/2020/06/18/better-buy-pfizer-vs-merck.aspx). I wanted to try to analyze the Merck and Pfizer stocks in pairs trading. 
I then used an SVR and LSTM model to predict the differences in the two stocks to evaluate when to pivot position between shorting and longing each one.

Statistical Measurements:
        
        Correlation between Merck and Pfizer is 0.706717
        Cointegration between Merck and Pfizer is 0.520267

Merck Risk Metrics:
      
        Alpha: 2.5
        Beta: .07
        Sharpe Ration : 49.9
        
Pfizer Risk Metrics:
        
        Alpha: inf
        Beta: .006
        Sharpe Ratio: 54.9

SVM Results:
      
        R^2: .92

LSTM Model:
      
        RMSE: .04 -> closer to 0 is better 

Graphical results see notebook
          
        
