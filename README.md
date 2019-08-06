# Multi-input-neural-net
House price predictions using images, numerical, categorical and unstructured text data through a combined functional neural net with Keras Tensorflow


Dataset:

Real Estate housing data from Allegheny County, Pennsylvania (drawn from Zillow.com) and housing data from Salt Lake County, Utah (drawn from KSL.com). 
The data includes information on the location of the home, various features about the home, and images of the home. 
 

Objective:

By using images we hope to more accurately predict the listing price of a home. 
We will build five models for price prediction.  The baseline model will be linear regression with numerical and categorical features. We will build three neural net models using numerical & categorical features only, one with images only, and one with unstructure text only. 
The fifth model we will build will be a combined neural net using the output layers of the 3 neural nets with the numerical/categorical features, images, and unstructured text. 
We expect the fifth model to outperform the baseline. Some of the features we are including from house listing are: zip code, bedrooms, bathrooms, lot size, finished square feet, yearBuilt, heating system, heating sources, cooling system, images, and text descriptions.


Evaluation Metrics:

Root-mean-square error will be used to evaluate the difference between our predicted price, and the listed price.  
