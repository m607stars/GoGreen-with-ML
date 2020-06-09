# Time Series for Wind Power Generation.  
<h3>Predicting the energy output of wind turbine based on weather condition</h3>

**Problem Definition** - Develop a time series model to Predict the power output of wind farm based on the weather condition in the site (1Hr prediction to 72Hrs. prediction) Build an application to recommend the Power Grid to suggest the best time to utilize the energy from wind farm

# Methods
1. In the dataset we are given the Wind Speed and Direction of the wind recoreded at a wind turbine. 
2. We consider the sin and cos components of the wind speed using the direction in our models so that each feature in the model is relatively similar in the context. 
3. First Used time series prediction using 4 different approaches to forecast the Sin and Cos components of the Wind Speed.
4. The Four Time Seires Approaches are Prophet, VAR, Holtwinters and GluonTS
5. 
* Having obtained the predicted wind speed and direction, we calculate estimated power generated using Neural Networks

# Libraries Used 
* <a href="https://facebook.github.io/prophet/" >Facebook Prophet</a>
* <a href="https://www.statsmodels.org/dev/generated/statsmodels.tsa.vector_ar.var_model.VAR.html?highlight=var#statsmodels.tsa.vector_ar.var_model.VAR" >Vector AutoRegression (VAR)</a>
* <a href="https://www.statsmodels.org/dev/generated/statsmodels.tsa.holtwinters.ExponentialSmoothing.html" >Exponential Smoothening Using HoltWinters</a>
* <a href="https://gluon-ts.mxnet.io/" >GluonTS(MXNet) DeepAREstimator</a>
* <a href="https://scikit-learn.org/stable/modules/neural_networks_supervised.html" >Multi-Layer perceptron (Neural Networks)</a>
* <a href="https://pandas.pydata.org/" >Pandas</a>
* <a href="https://numpy.org/" >Numpy</a>

# Acknowledgements 
* Dataset - https://www.kaggle.com/berkerisen/wind-turbine-scada-dataset
