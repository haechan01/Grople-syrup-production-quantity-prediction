# Grople-syrup-production-quantity-prediction
Click Grouple_syrup.ipynb to see the whole process of creating the machine learning model with detailed explanations. 

Summary: In this project, I used random forest algorithm to predict monthly production quantity of grople syrup in 10 different regions. 
Step 1: Data wrangling
There are four datasets in csv that can be used to predict grople quantity production in the regions: daily precipitation, daily soil moisture, daily temperature, and eight-day NDVI. Each of them have start date and end data of the measurement with region IDs. The data we are trying to predict, grople syrup production quantity, has a data record between 2015 and 2020, and it was measured monthly. Since the four predictor variables are measured several times every month with varying frequencies, I create a new dataframe that holds monthly average of the predictor variables and monthly grople syrup production. 

Step 2: Exploratory analysis
Here, I visualize the data and analyze summary statistics. 

Step 3: Model training


Step 4: Optimizing hyperparameters


Step 5: Final prediction with the machine learning model
