# Model-to-predict-life-expectancy-from-BMI-
Body mass index (BMI) is a value derived from the mass (weight) and height of a person. The BMI is defined as the body mass divided by the square of the body height.
In this section, we'll use linear regression to predict life expectancy from body mass index (BMI)
We'll be using scikit-learn's LinearRegression class
The data file can be found under the data.csv
It includes three columns, containing the following data: 1-Country, 2-Life expectancy, 3-BMI.
The steps for the model are:
1-Using pandas read_csv to load the data into a dataframe (Assign the dataframe to the variable bmi_life_data)
2-Creating a regression model using scikit-learn's LinearRegression and assign it to bmi_life_model and fit the model to the data.
3-Predict using a BMI for some countries
