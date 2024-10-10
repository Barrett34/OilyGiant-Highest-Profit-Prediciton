# OilyGiant-Highest-Profit-Prediciton
You work for the OilyGiant mining company. Your task is to find the best place for a new well.

## Project Intro:

In this project, we are working for a company named OilyGiant. We are tasked with finding the best place for a new well. To do this we collect oil well parameters in the selected regions. Next, we will build a model for predicting the volume of reserves in the new wells. After, we will pick the oil wells with the highest estimated values. Last, we will pick the region with the highest total profit for the selected wells. We will analyze profit and risks using the Bootstrapping technique.

## Data Description
Geological exploration data for the three regions are stored in files:

`geo_data_0.csv`
`geo_data_1.csv`
`geo_data_2.csv`
`id` — unique oil well identifier
`f0, f1, f2` — three features of points (their specific meaning is unimportant, but the features themselves are significant)
`product` — volume of reserves in the oil well (thousand barrels).


 ## Conclusion

 - We used a Linear Regression model for our predictions
- All the data was really well organized without missing values, dupes, or data type mismatches
- The data contained many outiliers that did not need removal
- The RMSE lowest value was located in Region 2. This is confirmed by Region 2 also being the region with the most accurate prediction results.
- The minimum volume required for each well was 111, but the average for each region does not reach that minimum.
- The highest profitable region is 1 at 33,208,260 USD. 
- With a 95% confidence interval, region 2 appears to be the safest choice for drilling wells.
