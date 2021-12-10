# SanDiego-Profitable Investment Properties
Project Video link : https://drive.google.com/file/d/1dQeps1aJXuxevkIVTwuwqPJusedqNX9m/view?usp=sharing
**Business Case and Value**
Business case is to find properties that are good investments.

An investor couldn't be more happier if he/she gets the combination of below 5 data, which could be profitable, affordable and safe. The objective of this project is to find such combination. Below are the given data which are directly related to the objective. We are trying to find such data, amalgamate them, do some analysis, prediction ad provide the accuracy to the data which we have formed.

**Good investment** = Rent Zestimate - Monthly Mortgage(HOA, Property Taxes, upKeep) > 0

Approach:

From dataset 1,2,3 we are trying to get the best features which can actually have a large impact on buying/investing in houses. Like,

For calculating Mortgage value we need 30 year fixed rate, which we have taken from 2nd dataset.
For Property Tax price calculation, we need property tax rate, which we have taken from 2nd dataset.
For an accurate calculation of Good investment we also need HOA, which we have taken from 2nd dataset.
Adding Crime rate data, definitely enhanced the dataset, added from 3rd dataset.
Added Average Income from 3rd dataset
Latent Variable = having the best combination above 5 data, which could be profitable, affordable and safe.

## Conslusion

Using fractal clustering, we can get more fine grained results which is more accurate than increasing the overall number of clusters initially. It helps in understanding which cluster to focus upon and do more in depth analysis on it. Also we found out feature importance can help a lot in using the important features and also reducing noise, for this we have leveraged gini scores, correlation matrix, PCA and shapley values. In this project, through fractal clustering we were able to find out the most profitable investment properties in San Diego through the Zillow dataset. These properties have the potential to generate positive cash flow through the property value minus expenses calculation. We can also conclude that enriching the data using amalgamation has resulted in more accuracy in classifiers and regressors. To find out which classifiers and regressors works best, we have created a loop to run all the classifiers and regressors and analyzed their metrics using accuracy, precision, recall and Mean Absolute Error. For future work, this project can be extended to other areas and also the data can be enriched with factors like past hazards, disaster prone zone, schools rating, neighborhood, amenities etc, which would give further insight into these properties.
