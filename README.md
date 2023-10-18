# Delhi House Price Prediction
The aim of this project to predict the price of the houses in Delhi, in various localities, based on the data present in the dataset. The dataset is from Kaggle. The project aims to predicts the house price, by analysing the features such as area, number of bedrooms, locality and many more. The dataset has 1259 rows and 11 columns.

## Data Dictionary
1. Area:- Area of the house in square feet
2. BHK:- Number of bedrooms
3. Bathroom:- Number of bathrooms
4. Furnishing:- Furnishing status
5. Locality:- Locality of the house
6. Parking:- Number of parking available
7. Price:- Price of the house in INR
8. Status:- property's status as in 'ready to move' or still under construction
9. Transaction:- Its a new property or being re-sold
10. Type:- Type of the property
11. Per_Sqft:- Price per square feet

## Conclusion
From the exploratory data analysis, we can conclude that the following features are important for predicting the price of a house in Delhi:
1. Area
2. BHK
3. Locality

From the EDA it was also found that, most of the houses in delhi are small having area between 100 to 200 sq. yards having 2-3 BHK. The price of the houses in localities such as Punjabi Bagh, Lajpat nagar and Vasant Kunj are high as compared to other localities, which means these are posh areas of Delhi. Most of the people prefer a new builder floor property despite the aprtments cost the same because people want to design their house according to their own needs and requirements and want more privacy and independency.

Coming to the machine learning models, I have used regression models - Decision Tree Regressor and Random Forest Regressor. The Random Forest regressor performed better than the Decision Tree Regressor with an accuracy of 78.70%
