# Exploratory Data Analysis and Logistic Regression Model Training

This project is a complete Exploratory Data Analysis on free to use banking data. The main goal of this project is to explore the data, analyze the statistical proprieties of the data and preparte it to train a Logistic Regression model to retrieve a predictive model 📊

## 📒 Key Takes

EDAs are the most important step before training a model. It's where you analyze the data, understand the data, clean the outliers, do a proper feature engineering to make sure the data you are feeding to your model will bring in the highest accuracy possible to the model. 
EDA normally study the Univariate and Multivarite relations of the Data, where the data distribution becomes clearer and open new paths to interpret it. There's a lot of plotting using Seaborn to understand the distribution of the Categorical features and Numerical features via histograms, boxplots and whatever kind of plot helps you vizualise the data: 

<img src="https://github.com/4GeeksAcademy/gustavolima-bank-eda/blob/main/assets/box.png" width="500">
<img src="https://github.com/4GeeksAcademy/gustavolima-bank-eda/blob/main/assets/histogram.png" width="500">


That exploration will lead then to heatmaps to understand the correlation between our data like we can see below: 

<img src="https://github.com/4GeeksAcademy/gustavolima-bank-eda/blob/main/assets/heatmap.png" width="500">


In this project the target was to understand if a customer would subscribe or not a new bank product, so the goal was to understand what combination of features would work best to target best the customer. For this problem Logistic Regression was the chose supervised learning method, with train and test datasets. The last step was to try and boost the model via the optimization of hyperparameters in order to get more out of it. 

I've achieved a good accuracy, but it leaves the door open to perhaps try Easy Ensemble with models that help with numerical problem solving. None the less, it was a fun project and interesting data set fo the real world to analyze and work on. 
