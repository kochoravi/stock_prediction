# stock_prediction
predicting the performance of stocks based on decade historical statistics and data of stock market. 

model_optimization_stocks_predict.ipynb
ML_key_stat.ipynb

Performing dimensionality reduction via principle component analysis and univariate feature selection and tuning the hyper parameters of the predictive models to improve estimator's accuracy scores.
The developed project performs three common methods of feature manipulation, dimensionality reduction and univariate feature selection to extract the relevant and informative feature. Here we construct a pipeline and start with dimensionality reduction using principle component analysis (PCA), Non-Negative Matrix Factorization (NMF). Logistics regression and support vector machine classifier uses the computed features to predict the "underperformed" and "outperformed" stocks and finally we compare the classification scores of optimal estimators after tuning the hyper parameters of the models. 
The best accuracy is reached by using most of the features (30 features). Due to inherent stochasticity of the stocks market prices based on over a decade historical data the maximum accuracy that is reached by the optimal classifier is (~69%). 

it constructs a pipeline that does dimensionality reduction followed by prediction with a support vector classifier. It demonstrates the use of GridSearchCV and Pipeline to optimize over different classes of estimators in a single CV run ? unsupervised PCA and NMF dimensionality reductions are compared to univariate feature selection during the grid search.


yahoo_stat_pull.ipynb 
Collecting-parsing large scale financial data and fundamental statistics from the HTML source code 
ML_key_stat: performing various machine learning classification algorithm (SVM, LGR) to predict the performance of 500+ companies based on over a decade of historical stocks market data. 
