//--Taking sample of the data comprising fields ->Home,Price,SqFt,Bedrooms,Bathrooms,Offers,Brick	Neighborhood.
//--Data.Info()->Detailed information about the null values of the data.
//--Data.Describe()->Detailed information about count, mean, std.
//-- Segregating numeric data (Numeric_Data= Data.select_dtypes(include= [np.number])
//Numeric_Data.head(5))
//--Segregating categorical values-->tring_Data= Data.select_dtypes(include=[np.object])
//String_Data.head(5)
//--Checking for null values on both numeric and categorical data
//--Replacing the categorical values with numbers
//--Testing for outliers using boxplot and z test .
//--Checking for normal distrbution by plotting the data using seaborn and getting bell curve.
//--Check for multi collinearity using heatmap.
//--Segregating dependent and independent variables [x='Brick','Neighborhood','Home','SqFt','Bedrooms','Offers'], Y=['Price'].
//--Training the model using sklearn (from sklearn.linear_model import LinearRegression
//lm= LinearRegression()
//lm.fit(X_train, Y_train) )
//--Printing test and train values (print (len (train_X))
//print ( len (test_X)))
//--Printing OLS Regresson Results
