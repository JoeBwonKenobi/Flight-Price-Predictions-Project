# **Flight Price Predictions Project**
 Predicting Flight Prices using Random Forest Regressor

# **Overview:**

This project uses data about flight prices to make predictions about the prices for a given route. The various steps taken were data cleaning, exploratory data analysis, visualizing the data to understand the trends of the ticket prices, training and evaluating a random forest regression model and build model inference using Flask. 


# **Visualizations:**

## **Airline vs Price Plot**

From the plot below we can conclude that Jet Airways business is the highest costing Airway.

![image](https://user-images.githubusercontent.com/117705408/233181015-4560061c-f9cd-4c25-a76b-8640fd481a57.png)

## **Source vs Price Plot**

The plot below says that if you are going from Bangalore, no matter where you are going, have to pay the highest amount of money.

![image](https://user-images.githubusercontent.com/117705408/233181042-de997b3b-0252-4b93-bf75-2faffd378151.png)

## **Destination vs Price Plot**

The plot below says that if you are going to New Delhi, regaurdless from where, you have to pay the highest amount of money compaired to other places in the data set.

![image](https://user-images.githubusercontent.com/117705408/233181069-26b6b46c-c7fc-43a1-ae27-bc6e840c8732.png)

## **Visualizing feature importance given by ExtraTreeRegressor**

![image](https://user-images.githubusercontent.com/117705408/233181385-81573773-97fc-4825-a5c5-48159e1e5cf7.png)

- Total_stops is the feature with the highest feature importance in deciding the Price as we have also seen above.

- After that Journey Day also plays a big role in deciding the Price. Prices are generally higher on weekends.

## **Plotting y_test vs Predictions**

![image](https://user-images.githubusercontent.com/117705408/233181776-7fe59dd5-3cee-45ff-8d46-139ce8debd69.png)

As we can see that most of the residuals are 0, which means the model is generalizing well.

![image](https://user-images.githubusercontent.com/117705408/233181538-eb821af6-333b-45bf-8936-de35659f6f3f.png)




Project source link: https://machinelearningprojects.net/flight-price-prediction/
