# HMDA-EnsembleLearning
Analysis of HMDA using ensemble learning algorithms.


***Unable to upload to GitHub because the data file is too large, it can be obtained from here：[Dataset](https://www.dropbox.com/s/6e9xy2dag8o3kph/Washington_State_HDMA-2016.csv?dl=0)***

***
You can also download it from the official website of kaggle：
[complete dataset](https://www.kaggle.com/datasets/miker400/washington-state-home-mortgage-hdma2016)

***
HMDA (The Home Mortgage Disclosure Act) is a bill in the United States, which stipulates that financial institutions must disclose the data of mortgage loans to the whole society. These data help show whether lenders are serving customers with real housing-related needs. Analysis of these data can assist government officials in their decision-making and potentially reveal some discriminatory lending patterns. The original data contains a total of 47 variables, and the target variable is action_taken_name, which can be simply understood as the result of applying for a loan. The main goal of this case is to explore whether certain information or behaviors of the applicant will affect the prediction of the final loan grant, so that Show a complete data mining process. (Washington_State_HDMA-2016.csv)



This project follows the general process of data mining. First, read the data that has been downloaded locally. After regular exploration, perform data preprocessing, and then directly select the decision tree, random forest, GDBT, and XGBoost algorithms in the sklearn module for modeling , select a model with outstanding performance for further parameter tuning optimization, and finally confirm the model and make predictions.

![image](https://user-images.githubusercontent.com/68887123/225375182-3efdb644-3ad7-4d55-9933-609b82569e07.png)


This project mainly introduces how to conduct modeling analysis for the actual classification problem, and uses various methods for model comparison, and finally chooses the XGBoost algorithm for model training, and then predicts the results of customer applications for loan products. In terms of model parameter optimization, the grid search method is used to search for the optimal model parameters, so as to find the optimal model parameters and effectively improve the accuracy of the model. The experimental results show that this process can be used to predict and analyze such classification problems, and the effect is relatively good. It can be used as an effective means to solve this kind of data analysis and mining algorithms. Of course, there is still room for improvement in model accuracy. Learners can use the knowledge they have learned in feature engineering, model selection, and model parameter optimization to find the optimal model and obtain a better classification model.
