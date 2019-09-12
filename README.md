# stock_pred
Machine  learning with python on stock prediction with TATA globals company Dataset.

///////////////////////////////////////////////////////////////  
NSE-TATAGLOBAL.csv   -- Dataset frame

stock__pred_final1.ipynb  -- Jupyter Notebook file

///////////////////////////////////////////////////////////////

In any stock market or in share exchange the profit or loss calculation is usually determined by the closing price of a stock for the day of the company.

so here we create a dataframe with only the Date and Close price columns of the data.

## Methods
**1)linear_regression:**
           
            It is no good in this method since it has time_stamp basic of  working so it always increases and the close columns data varies indifferently. so we cant use linear_regression.
   
   **2)average_method:**
   
             It is tried out in this but the predicted value is not nearly close enough.
            
            
             OUTPUT::
 ![average_method_out](/images/average_method.png)

    
Thus we need time series forecasting techniques to be used in our model to get the best outcome. 

  **3)ARIMA_method:**

            ARIMA model uses past data to understand the pattern in the time series it is seen that this model predicted the trend in the series.
            In stock it does not have a particular trend of it changes frequently so we need both trend and seasonality with higher intelligence of prediction.

            From the ARIMA_method we can see that the model gives the trend in the data.but we need to predict the data for time to time.  
  

            OUTPUT:::
![method_out](/images/ARIMA_method.png)


 SO we need a model which can store past information that is important and forget which are not important.


  **4)LSTM_model:**
  
              LSTM is able to store past information that is important, and forget the information that is not and gives great accuracy of data in predicting the data.
  

             OUTPUT::     
![LSTM_method_out](/images/LSTM_method.png)
            
