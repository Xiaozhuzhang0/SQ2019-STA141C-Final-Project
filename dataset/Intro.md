**Note:To download the csv files, click on it and select `view raw`. Right click on the screen and select `save as` csv file.**

**1.price_predict_reduced.csv:** 
  *  Text data. 10000 rows
  *  https://www.kaggle.com/c/mercari-price-suggestion-challenge/data
  *  This data is part of the original training data. The original dataset has over 1 million row and 10000 of the rows were randomly sampled. The original dataset has 7 attributes and I concatenate the 4 text column into a single column. Now the data frame has two column:text description and the corresponding price.
  
**2.Violent_Crime_Pred.csv**
  *  1994x125 (moderate high in feature, numeric attributes, contains irrelevant features) 
  *  https://archive.ics.uci.edu/ml/datasets/Communities+and+Crime+Unnormalized 
  *  This dataset is on the community information(socioeconomic, ethnic) and the instances of crimes in the community. There are 125 (predictive) attributes and the target attribute is the number of violent crimes per 100k population. The detailed description of the attributes can be found in the link. This dataset contains many extra predictive columns. Note that the some rows were removed due to missing values in target value column.
  
**3.Admission_Predict.csv**
  *  400x7 Small dataset, low dimension
  *  https://www.kaggle.com/mohansacharya/graduate-admissions
  *  We want to predict the chance of being admitted into graduate school

**4.pass_testing.csv**
  * https://www.kaggle.com/c/mercedes-benz-greener-manufacturing/data
  * 4210*377 sparse dataset, binary and categorical variable 
  * We want to predict the time (in seconds) that the car took to pass testing 

**5.Automobile.csv**
  * http://archive.ics.uci.edu/ml/datasets/Automobile(on github)
  * 205*26(categorical attributes and numerical attributes)
  * Predict the price of the cars given their characteristics. 

**6.Predict Property value**
  *  https://www.kaggle.com/c/sberbank-russian-housing-market/data
  *  30500*292 large scale data (data available in csv format in the link)
  *  Summary: This is a kaggle challenge which contains datasets on home value and associated features. This dataset might be an example of the type of data that has a lot more samples than features. There are a couple of other files in the kaggle website, we will be using the train.csv and test csv.
