# Optimal Rental Property Pricing by Region
***
Capstone project for the AI academy 

Contributor: Colton Lineman 

![Money](https://media.altpress.com/uploads/2018/06/make_money_gif.gif)

All final models are including the [presentation](https://github.com/cLineman/Rental-Property-Prediction-Model/blob/main/Final%20Power%20Point.pdf) and the [Juptyer notebook](https://github.com/cLineman/Rental-Property-Prediction-Model/blob/main/Final%20Notebook.ipynb). For [personal notebooks](https://github.com/cLineman/Rental-Property-Prediction-Model/tree/main/Working%20Notebooks) and the [data set](https://github.com/cLineman/Rental-Property-Prediction-Model/tree/main/Dataset)


## Project Description
***
For this project, I did reach into Airbnb property pricing. I used this data to predict pricing based off region and other data to find the most competitive price for the property.
I used two models to come to my conclusion that an XGBoost is the best model to use to predict the most completive price to price your rental property. This Will increase profit by optimizing the price to maximize the amount of time the property is rented at the best price for profit.

![Going Up](https://media1.tenor.com/images/fa0bd5b188840241312b1f35ade00b9f/tenor.gif?itemid=15715298)

### Data Sources
***
* [Airbnb Rental Property](https://www.kaggle.com/datasets/kritikseth/us-airbnb-open-data?resource=download)


### Presentation
***
https://github.com/cLineman/Rental-Property-Prediction-Model/blob/main/Final%20Power%20Point.pdf


### Data Interpretation and Analysis
***
I started the process by cleaning a data set I found on kaggle. I then ran some visulaizations to get an understanding of the data and see if there are any biases I should understand before working with the models.

I then preformed two prediction models (Decision Tree and XGBoost) with the point of focus being price. In doing this I used feature engineering to help increase the accuracy of the models.

### Findings and Recommendations
***
My investigation found that an XGBoost was the superior model over a decision tree. It was better because:
- The accuracy was higher
- The runtime was not substantially long enough to be deemed unfit
This means to find the best possible price you should use an XGBoost. For you, this means that an XGBoost will optimize your pricing to maximize your profits

![Bring me My Money](https://media0.giphy.com/media/XZmzFsNQETSFrXVDYr/giphy.gif?cid=790b7611539f28bea0b1ac55a9e7cd7875dd7c28bade4fd6&rid=giphy.gif&ct=g)

#### Acknowledgements
***
*https://github.com/python/cpython/blob/3.10/Lib/warnings.py  
*https://github.com/python/cpython/blob/3.10/Lib/zipfile.py  
*https://jupyter.org/  
*https://matplotlib.org/  
*https://matplotlib.org/  
*https://numpy.org/  
*https://pandas.pydata.org/  
*https://plotly.com/python/  
*https://pypi.org/project/tabulate/  
*https://scipy.org/  
*https://seaborn.pydata.org/ 
*https://www.statsmodels.org/stable/index.html
*https://pypi.org/project/wordcloud/
*https://xgboost.readthedocs.io/en/latest/python/python_api.html
*https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html
*https://xgboost.readthedocs.io/en/stable/
*https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html
*https://snyk.io/advisor/python/xgboost/functions/xgboost.plot_importance
*https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.resample.html
*https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html
*https://scikit-learn.org/stable/modules/generated/sklearn.tree.plot_tree.html
*https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html
*https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html

*[Panda](https://www.publicdomainpictures.net/en/view-image.php?image=45712&picture=panda-bear) - Ronald Carson

[Python 3.9.12](https://www.python.org/) Copyright ©2001-2022. [Python Software Foundation](https://www.python.org/psf-landing/)