# Final_Project
<<<<<<< HEAD

=======
>>>>>>> master
- Since this Covid_19 beakout becoame True, people all over the world started asking how far this pandamic will go.
- people are asking questions such as: how many people are expected to get the Virus?
how many are going to recover?
and how many are expected to die?
- there are an official statistics and predictions 
- some of this predictions are very close to the real numbers but there are still some new waves of the virus hitting 
some states in the USA.
- our Analysis is about using histroric datasets to predict a numbers of death by COVID_19.
- We used data from "https://healthdata.gov/dataset/covid-19-cases-tests-and-deaths-zip-code", the data is cleaned using Excel and pandas.
- we used machine learning and trained our data then used Linear Regission model.
- Linear regression is the simplest and most widely used statistical technique for predictive modeling. It basically gives us an equation, where we have our features as independent variables, on which our target variable [sales in our case] is dependent upon. source: "https://www.analyticsvidhya.com/blog/2017/06/a-comprehensive-guide-for-linear-ridge-and-lasso-regression/"
- the Model's accuaray is high 0.94, but to make sure it is functioning right we introduced three more models to compare between them.
- the models we used are ; LASSO and RIDGE 
- Lasso regression is a type of linear regression that uses shrinkage. Shrinkage is where data values are shrunk towards a central point, like the mean. The lasso procedure encourages simple, sparse models (i.e. models with fewer parameters). This particular type of regression is well-suited for models showing high levels of muticollinearity or when you want to automate certain parts of model selection, like variable selection/parameter elimination.
source:"https://www.statisticshowto.com/lasso-regression/"
- Ridge Regression is a technique for analyzing multiple regression data that suffer from multicollinearity. When
multicollinearity occurs, least squares estimates are unbiased, but their variances are large so they may be far from
the true value. By adding a degree of bias to the regression estimates, ridge regression reduces the standard errors.
It is hoped that the net effect will be to give estimates that are more reliable. Another biased regression technique,
principal components regression, is also available in NCSS. Ridge regression is the more popular of the two
methods. source: "https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Ridge_Regression.pdf"
-the Hypothesis of the Analysis:
- the higher the weekly rate the higher the weekly deaths.
