# **Flight Price Predictions Project**

![image](https://github.com/JoeBwonKenobi/Flight-Price-Predictions-Project/assets/117705408/017bf431-f385-4a45-a5a7-dc26f7769404)


 Predicting Flight Prices using Random Forest Regressor.

# **Overview:**

This project uses data about flight prices to make predictions about the prices for a given route. The various steps taken were data cleaning, exploratory data analysis, visualizing the data to understand the trends of the ticket prices, training and evaluating a random forest regression model and build model inference using Flask. 

# **Data Source:**

Project source link: https://machinelearningprojects.net/flight-price-prediction/

# **Methods**

I used an Extra Tree Regressor model to predict flight prices. I cleaned the data, performed exploratory data analysis, visualized the data to understand the trends of ticket prices, trained and evaluated the model, and built the model inference using Flask.
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

- Simply plotting our predictions vs the true values.
- Ideally, it should be a straight line.

# **Recommendations:**

The provided insights can pait a larger picture of which airlines have higher prices based on destinations of departure and arrival. The trends and patterns provided can give executives an oppurtunity to examine the potential for necessary changes. 
total stops seemed to make an profound impact on flight price, as did distance and day of the week as flights were generally higher on weekends.

# **Limitations & Next Steps:**

This predictions model is limited to the dat it was given, meaning if it were possible to obtian more data about past flights it would perform better. There are many steps that could be taken from here including implementing a plan for maximizing profits, making logistics more efficent, and looking into where to build more airports based on the insights provided. 
