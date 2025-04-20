How to implement the generated models to predict CPU performance

1) Use extract-benchmark-data.ipynb to extract the latest 1000 benchmark data from the web

2) Use CPUdata_avg_std.ipynb to get the standard deviation of the data

3) Use CPUdata_norm.ipynb to normalize the data

4) Use CPUdata_stat.ipynb to get the rolling average of the data as a last step in data preparation

5) Now run modellingData.ipynb to utilize the three models (linear regression, support vector regression, and finally Recurrent Neural Network) to generate models with graphical representations of the data

6) These models will provide accurate insight and predictions to any processor's performance be it single-core or multi-core
