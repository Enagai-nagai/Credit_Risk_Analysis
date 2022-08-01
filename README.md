# Credit_Risk_Analysis

# The purpose of the analysis
In this analysis, we predict if someone's credit risk is high or low using our loan_stats.csv data.
As the number of low risk is quite low compared to that of high risk, we need to consider using resampling process (oversampling and undersampling). 
Here, 6 resampling methods were applied and we will analyze which modeling works the best.

# Results
Here is the list of results.


* Oversampling
![image](https://user-images.githubusercontent.com/99149443/182074051-c022ba64-df28-4b8c-bf3f-4a5487b61767.png)

*  SMOTE
![image](https://user-images.githubusercontent.com/99149443/182073993-6e595c03-927d-49d6-97c8-0aaeb791dd36.png)

* Undersampling
![image](https://user-images.githubusercontent.com/99149443/182074131-dfa3a78b-3dc7-47b9-a63a-89270769c735.png)

* Combination of Oversampling and undersampling
![image](https://user-images.githubusercontent.com/99149443/182074186-0d1f70fd-26f9-402a-a25a-7d1f5eb52572.png)


* Balanced Random Classifier
![image](https://user-images.githubusercontent.com/99149443/182074254-5faf5ba8-3e9e-491a-ad9a-132cc5953fbf.png)


* Easy Ensemble AdaBoost
![image](https://user-images.githubusercontent.com/99149443/182074305-5d8f4c7e-e44e-4df8-b53d-2811d4f1efb7.png)


# Summary
* Applying oversampling/undersampling doesn't necessarily improve the accuracy of the model.
* Among the 6 models we created, the last one used with Easy Ensemble Adaboost shows the highest accuracy.
