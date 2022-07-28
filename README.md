# Car-Price-prediction
Built a Machine Learning Model to Predict the Price of a Car.

![GetPaidStock com -62e2916cc45c5](https://user-images.githubusercontent.com/73393430/181519378-10d52454-211c-4384-aff0-fcd9071dc277.jpg)

# Problem Statement
Great Motors deals in used cars, with a huge market base in Nigeria. The company has a unique platform where customers can buy and sell cars. A seller posts details about the vehicle for review by the company’s mechanic on the platform to ascertain the vehicle's value. The company then lists the car for sale at the best price. Great Motors makes its profit by receiving a percentage of the selling price listed on the company platform. To ensure the car's selling price is the best for both the customer selling the vehicle and Great Motors, you have been assigned the task of coming up with a predictive model for determining the price of the car.

Your job is to predict the price the company should sell a car based on the available data the mechanics have submitted to you.

The objective of the challenge is to predict the price (Amount (Million Naira) the company should sell a car based on the available data (Location, Maker, Model, Year, Colour, Amount (Million Naira), Type, Distance). The objective is the predict the selling price.

# Methodology Used
## Python Libraries

- Pandas: For loading data file into a dataframe and for data wrangling.
- Numpy: Used to perform some numerical computations.
- Seaborn: For data Visualization.
- Plotly Express: Used for more complex visualization Seaborn can not perform.
- NLP (re and NLKT Library): Used to Tokenize the model of cars so we can extract meaningful tokens from it.
- Scikit-Learn: Used for Machine Learning Tasks.
- Catboost: The Final Estimator used to Predict the Price of the Car.

# Useful EDA
It was seen from the dataset on average the top ten most expensive cars:
![download (1)](https://user-images.githubusercontent.com/73393430/181519842-dbbc9471-14dc-4367-9484-7481fbc974cc.png)

Also it was seen that the most type of cars customers uses are centered around the foreign type of car.
![download (2)](https://user-images.githubusercontent.com/73393430/181519999-05b5c806-bd72-44c6-ac8f-d3e0a5510aed.png)
