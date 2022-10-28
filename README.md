# Thyroid_detection


Problem statement is to build a classification model to predict the type of thyroid based values given. This Project completely based end to end pipeline from getting the data from client ,storing in database to predicting the values.
Possible usage - Model can be used by hospitals to smoothen there workflow . Depending on whether a person has thyroid or not, if YES then what kind it is and if it is hyperthyroid or patience require immediate assistance report will be directed to senior doctor and if is –ve or mild report(Hypothyroid) report will go to junior doctors (also will check whether model has correctly predicted).
In this project data is validated then stored in the database, csv file is extracted and feeded to training pipeline which involve dividing data into clusters and create separate models for individual clusters. Prediction route is called separately and predictions are done based clusters assigned and using models saved.
