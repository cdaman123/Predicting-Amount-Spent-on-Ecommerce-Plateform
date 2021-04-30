# Predicting-Amount-Spent-on-Ecommerce-Plateform

In this project we use Linear Regression for predicting spent time of a customer using the previous data set of a E-commerce company.


Dataset has Customer info, suchas Email, Address, and their color Avatar. Then it also has numerical value columns:
* Avg. Session Length: Average session of in-store style advice sessions.
* Time on App: Average time spent on App in minutes
* Time on Website: Average time spent on Website in minutes
* Length of Membership: How many years the customer has been a member.
### Dataset Info : 
```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 500 entries, 0 to 499
Data columns (total 8 columns):
Email                   500 non-null object
Address                 500 non-null object
Avatar                  500 non-null object
Avg. Session Length     500 non-null float64
Time on App             500 non-null float64
Time on Website         500 non-null float64
Length of Membership    500 non-null float64
Yearly Amount Spent     500 non-null float64
dtypes: float64(5), object(3)
memory usage: 31.3+ KB
```
After EDA I train a Linear Regressor and get these evalution of model:

```
MAE: 7.228148653430838
MSE: 79.81305165097461
RMSE: 8.933815066978642
```
