# Walmart-Weekly-Sales

A [kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting) competition where we have to predict weekly sales of stores of *Walmart*.

After *cleaning and Merging* of the Data **EDA Result** is following :-

- The Graph of *Date* vs *Weekly_Sales* is as follows :-

<center><img src='/Images/time_with_sales.png' width='700px' height='400px'></center>

- The Pair plot between *MarkDown* variables and *Weekly_Sales* is as follows:-

<center><img src='/Images/mark_vs_sales.png' width='900px' height='600px'></center>

- The Scatter plot between *Other* variables and *Weekly_Sales* is as follows :-

<center><img src='/Images/other_vs_sales.png' width='900px' height='600px'></center>

- Correlation heatmap between *int* type variables are as follows :-

<center><img src='/Images/correlation.png' width='800px' height='550px'></center>

After **EDA** of the Data, I created **Regression Model** to fit the Data. The **Models** are as follows :-

```python
models = [LinearRegression, KNeighborsRegressor, XGBRegressor, RandomForestRegressor]
```

I used **KFold CV** to train the **Models**. After training the results are of different **Models** are as follows :-

<center><img src='/Images/lin_poly.png' width='300px' height='120px'></center>
<center><img src='/Images/other_model.png' width='300px' height='480px'></center>
