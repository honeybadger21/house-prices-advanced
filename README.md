# house-prices-advanced

Solution Description:
As an attempt to get hands-on practice with prediction problems, I picked up the Advanced House Prices dataset with 80 predictors, each consiting of 1460 data points. Starting with some exploratory data analysis, I performed categorical features encoding, imputed missing values, and checked for skewness. Finally, used Lasso, Elastic Net, Kernel Ridge, Gradient Boost, and XGBoost for prediction (with cross validations). The evalution metric was RMSLE. Gradient Boost turned out to be the best performing model but Lasso also performed at par. 

Concerns and WIP:
While working with this dataset, I encountered some questions that I am still finding answers to. I am putting them here as a work-in-progress to keep a track of my thoughts associated with this particular problem:
1. Given the already huge number of features, of which a great chunk being categorical, standard encoding or pd_dummies will just increase the size of the feature space. It went from 80 to 221 in this case. Here, what could be some alternative methods to deal with categorical features? One method that I can recall from my Advanced Machine Learning lectures at UT Austin is frequency-based encoding but I am yet to implement that. 
2. What is the impact of skewness in the data to our regression models? Yes, we check skewness and do all sorts of log/Box-Cox transformations, but I am yet to understand why that's done and what's the impact?

I am still working on trying and testing out some different feature treatment methods and will keep updating this space for changes. 
