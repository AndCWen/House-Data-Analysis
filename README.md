# House Data Analysis

In the IBM Data Science certification, I learned about using Python for analysing data and developing models to predict the value of one variable using other variables and features. This can be incredibly useful for tasks such as predicting the price of a house based on the house's characteristics. This house data analysis is one of the projects I completed in the course. 

# Steps I Took:

## Step 1: Importing The Data
Skills Network Lab supplied the data, I downloaded it into my browser then created a dataframe from the data in the csv. I then took some time to explore the data and get a statistical summary of the data so I knew how to work with it. 

## Step 2: Data Wrangling
Next, there was some cleanup needed. For instance, a couple of columns were not needed so I dropped those. There were also a couple of columns missing values, so I replaced them with the mean value of that column. 

## Step 3: Exploratory Analysis 
Next I explored the data to see any general patterns or relationships. This included creating some visualizations, such as the ones below, that evaluated the relationship of some of the variables with the price of the home. 

![image](https://github.com/AndCWen/House-Data-Analysis/assets/132102517/ab011e92-38eb-41d6-b593-073f641fc652)


Waterfront houses do tend to be a bit more expensive, but there are certainly quite a few outliers of pricy houses that are not near water.

![image](https://github.com/AndCWen/House-Data-Analysis/assets/132102517/758255cf-cd90-4e3c-928e-793d85624557)


Square footage has a positive correlation with price, which makes sense that a larger house would typically cost more.


## Step 4: Model Development
This next section was focused on creating models for predicting the price of a house based on different variables, such as square footage, then evaluating the model by the R^2.  At the end, I found using a list of several features to predict price gave me an R^2 of .65, which is worth while. 

## Step 5: Model Evaluation and Refinement
This final step involved splitting the data into training and testing sets, then evaluating and refining the model as needed. 


