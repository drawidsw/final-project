# Overview

Check [this](README.md) for the introduction of the project. 

# Machine Learning Model Results

To predict the price of a house based on factors, we ran two different *supervised ML models* in three different stages. In the first stage, a *base* model consisting of only the attributes of the house was used. In the second stage, school ratings enrichment data was added. Finally, demographics (per zip code) enrichment datw was added. 80% of the data was used for training and 20% was used for testing in each case. The table below shows the *meansquare error* (MSE), and the R<sup>2</sup> coefficient showing the model's accuracy.

| Model | MSE (Multiplied by 10<sup>9</sup> | R<sup>2</sup> Training | R<sup>2</sup> Testing |
| ----- | --------------------------------- | ---------------------- | --------------------- |
| Multiple Linear Regression (Base) | 55.09 | 0.67 | 0.66 |
| Random Forrest, n=30 (Base) | 45.5 | 0.96 | 0.72 |
| Multiple Linear Regression (School Ratings) | 38.13 | 0.76 | 0.76 |
| Random Forrest, n=30 (School Ratings) | 18.61 | 0.98 | 0.88 |
| Multiple Linear Regression (All Enrichment) | 35.12 | 0.78 | 0.78 |
| Random Forrest, n=30 (All Enrichment) | 16.1 | 0.98 | 0.9 |

## Results Explanation

* The accuracy of the base model for the test data topped out at R<sup>2</sup> value of 0.72. On its own merit, this is an acceptable result. The figure below shows the graph of actual versus predicted price to corroborate this finding.

![](images-ml-models/model1.png)

* However, when the school ratings enrichment data is added, the testing data R<sup>2</sup> accuracy improved to a very high 0.88. The MSE also reduced from 55.09 to 18.61, an almost 67% reduction. This shows the school ratings are an important predictor for the sales price of a house. The graph of the actual versus predicted prices below looks more tidy now.

![](images-ml-models/model2_plot2.png)

* In the final phase, demographics data was added summarized as ethnic breakdown per zip code. This slightly improved the model accuracy as shown in the picture below and the values in the table above.

![](images-ml-models/model3.png)

* We plotted the percentage deviation of the predicted price versus the actual sales price. The graph below shows that the percent deviation *does not* depend upon the actual price. This is good, because our model can be confidently used to predict the price of a house at any value.

![](images-ml-models/insight4.png)


## Important Predictors



