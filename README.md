## Predicting Advertising Budget Sales
#### By Olujimi Fashoyin

### Dataset
>The dataset consists of 200 entries entries and 4 features. The dataset shows  the budget spent on each advertisment and the amount of sales made. I am concerned about what feature best affect the sales in other to predict the amount of sales that would be made if a different budget was placed on the feature.  The Dataset can be downloaded using this [link](https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset/download?datasetVersionNumber=1)

### Libraries Used:
 - Pandas
 - Matplotlib
 - Numpy
 
### Summary Findings:
> In summary, After properly cleaning and visualizing the data, I saw that the TV_Ad_Budget(Feature) had a strong positive linear correlation with the Sales(Labels) so I split my feature and labels into training and test set and created, trained and tested my model using the feature and label to accurately predict the sales that would be made for future budget prices put on the TV_Ad_Budget feature.  

### Key insights:
> I did not use the scikit learn library in this project intentionally. I wanted to practice the mathematical knowledge I gained on linear regression on a real life dataset. 
>> **NB**: I got an Rsquare score of 60% while training and an Rsquare score of 99.9% while testing
