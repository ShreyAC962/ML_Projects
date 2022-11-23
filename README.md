# ML_Project-MiniProject

CALORIE BURNT PREDICTION

    In this project we have used an XGBoost Regressor model to predict the accuracy of the trained XGBoost Regressor model(that is the Mean absolute Error of the predicted and original calorie values).
    Here we have used numpy,pandas,sklearn,seaborn,matplotlib,XGBRegressor,train_test_split dependencies.
    Initially the data is collected from the kagael that is from the fmendes-DAT263x-demos data set which consits of two files in .csv format( 1st file-calories.csv consits of User_ID,Calories) and (2nd file-exercise.csv consits of all the features(height,weight,gender,age,heart_rate,body_temp,User_ID) then load the data from the csv file into pandas dataframe and then concatenate both the dataframes and then process the data if any missing values are found.
    Then analyse and visualize the data with the help of seaborn,matplotlib.
    Next convert the categeorical columns(text data) into numerical values and then seperate the target data(calories) from the feature data.
    Then split the data into training and testing data.
    Train the model(XGBRegressor) with the help of training data and Evaluate the model with the help of testing data (To get the accuarcy of the trained model).
    
    Dataset:https://www.kaggle.com/datasets/fmendes/fmendesdat263xdemos
