This project is the Capstone Project of my Udacity Data Science Nanodegree.
For this project I analysed a dataset from Starbucks containing information about different offers that were provided to their customers.

The goal of the project will be to predict whether an offer will be successful or not. A successful offer will generate transactions and therefore revenue for Starbucks. The data provided is simulated data that mimics the behavior of customers in the Starbucks rewards mobile app. The model I will be building should be able to predict the probability of an offer to be successful and as a conclusion whether it is useful to place it in the mobile app for the customers to use. A difficulty will be to identify what transaction were made based on the provided offers and would not have been made anyways. If we provide an offer to a customer that would make a transaction anyway we would lose revenue.

This goal can be achieved by following the below-mentioned strategies:

Exploring and Visualizaing the Data.
Applying Quick Data Analysis.
Preprocessing the data.
Scaling the numerical features.
Trying several Supervised Learning Models.
Evaluating the models using the chosen metric (Accuracy)- Choosing the best model among them.
If the results need to be improved, implementing GridSearchCV to find the best parameters (in order to improve the performance of the chosen model).

All neccessary packages are referenced in the Requirements.txt file.
File Description:
* data - contains the three different datasets: 
  * portfolio.json - containing ids and meta information about the offers
  * profile.json - containing ids and demographic information about the customers
  * transcript.json - containng information about the records for transactions, offers received, offers viewed, and offers completed
* Starbucks_Capstone_notebook.ipynb - Notebook containing the analysis and the model training used in the project
* Requirements.txt - Containing the requirements and packages used for the environment the analysis run in
* Success of Starbuck's Offers_by Patrick Beckmann_Feb, 2023_Medium.html - The html containing the blog post I made on medium about that project
* pic1.png - a picture used in the description of the notebook
* pic2.png - a picture used in the description of the notebook

I also wrote an [article on medium](https://medium.com/@patrick.beckmann/success-of-starbucks-offers-7f64df027a07) about my project.

References:
https://towardsdatascience.com/top-10-binary-classification-algorithms-a-beginners-guide-feeacbd7a3e2
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.VotingClassifier.html
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.AdaBoostClassifier.html
https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.LinearDiscriminantAnalysis.html
https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html
https://scikit-learn.org/stable/modules/svm.html#svm-classification
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
https://github.com/VishalkrishnaBlaze/Starbucks-Capstone-Challenge
https://github.com/jdabel123/Udacity-CapstoneProject-Starbucks
https://github.com/Swatichanchal/Starbucks-Capstone-Project
