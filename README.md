# Time-series-Forecasting-of-Stock-Market
# Project Objective & Workflow 

The objective of this project is to create a model that can forecast the next
month of Close price.
here are the steps that need to be done:


1.    **Data wrangling and preprocessing** 
    * Handle Mising Values: Calculate the number of missing values & Impute the missing values.
    * Handling Categorical Values: Express each variable as a numerical value (all data is originally stored as strings).
    * Resample the data by month.


2.  **Feature engineering**
    * Identify any seasonality (Yearly,Monthly)
    * Split the DateTime object into Month and Year columns.
    * Scale the data

3. **Split the data**
    * Make a 70:20:10 split to create training, validation, and test sets.

4. **Prepare for deep learning modeling**
    * Implement the DataWindow class.
    * Define the compile_and_fit function.
    * Create a dictionary of column indices and column names.

5. **Model with deep learning**
    * **Train two baseline model.** 
    * **Train a linear model.** 
    * **Train a deep neural network.**  
    * **Train an LSTM.** 
    * **Train a CNN.** 
    * **Train a combination of LSTM and CNN.** 
    * **Train an autoregressive LSTM.** 
    * Select the best-performing model.
