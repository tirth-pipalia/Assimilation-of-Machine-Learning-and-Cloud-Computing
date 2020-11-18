# Assimilation-of-Machine-Learning-and-Cloud-Computing
Business Analysis, Machine Learning, AWS Cloud Technologies applied for finding solutions in Supply Chain Industry

## Table of Contennt
* [Abstract](#abstract)
* [Research Questions and Objectives](#research-questions-and-objectives)
* [Data Collection](#data-collection)
* [Exploratory Data Analysis](#exploratory-data-analysis)
* [Analysis and Findings](#analysis-and-Findings)
* [Conclusion](#conclusion)
* [Technologies Used](#technologies-used)
* [Bug / Future Request](#bug-/-future-request)
* [License](#license)

## Abstract
During the era of IoT and Big Data as an emerging technology, it has major impact on all the
business sectors. This technology results in generating massive amount of electronic data
which contains valuable information. To extract and analyse this information at greater scale
the only choice is Cloud computing and Machine Learning technology. The goal is to identify
best process for Fraud Prediction and Sales prediction. Ten Machine Learning models are
implemented for solving this business question. RandomizedSearchCV is implemented for
hyper parameter tuning and time required by model for training and prediction is also
evaluated. Even SMOTE is applied for imbalanced dataset. Classification models are validated
based on Recall, F1, Confusion Matric ROC-AUC values. Regression Models are evaluated
based on MAE and MSE score. Research is conducted using Amazon Web Services and python
for predictive analytics by assimilating Machine Learning and Cloud Computing technologies.<br>
Keywords: Amazon Web Services, SMOTE, RandomizedSearchCV, Predictive Analytics,
Machine Learning


##  Research Questions and Objectives
• To what extent cloud computing and machine learning techniques be effectively
assimilated with supply chain industry to predict fraud and sales?<br>
• What will be Obstacles and Opportunities for applying machine learning and data
mining techniques in the supply chain industry? <br>
• Which variables and features are important for Fraud Detection and Sales Prediction? <br>
• Which model is the best fit for Fraud Detection and Sales Prediction? <br>
These questions assist in defining the objectives: <br>
- To discover common dataset for Fraud and Sales prediction so that inter-relationships
between of features can be highlighted with respect to fraud and sales. <br>
- Obtain critical and comprehensive literature review for related research work. From
concrete sources like Journal Articles, ML Conferences, Books, Research Papers. <br>
- Perform EDA (Exploratory Data Analysis) for generating preliminary insights from the
dataset. <br>
- Setting up the hyper-parameters for essential Machine Learning model using
RandomizedSearchCV. <br>
- Feature engineering to obtain the impact of important features in the dataset.
- Evaluate and validate results of ML models using metrics like Accuracy, F1, Recall Score
and RMSE, MAE values. <br>
- Setting up the services of AWS which will make the implementation of predictive
analysis easier and efficient. <br>
- Setting up AWS S3 permission and installation of essential packages for performing
cloud integration task. <br>

## Data Collection
The [dataset](https://data.mendeley.com/datasets/8gx2fvg2k6/5) used for research is the fusion of primary and secondary data as it was
collected by other people who are not involved in this research however data is utilized for
achieving the objective of this research. Dataset was first uploaded on (Share & Manage
Research Datasets - Mendeley, 2019) based in London UK, provides research and academic
services developed by (Elsevier | An Information Analytics Business | Empowering
Knowledge, 2008). (Constante, Silva and Pereira, 2019) are the contributors of the dataset
who have uploaded 5 versions of dataset amongst which 5th version of the dataset is utilized
for the research. Dataset has CC BY 4.0 licence and was collected to fulfil the requirements of
Supply Chain for Big Data Analytics, Machine Learning Algorithms, and for areas of important
registered activities of Commercial Distribution, Sales Production, Fraud prediction, as such.

## Research Questions and Objectives
<br>
• To what extent cloud computing and machine learning techniques be effectively
assimilated with supply chain industry to predict fraud and sales? <br>
• What will be Obstacles and Opportunities for applying machine learning and data
mining techniques in the supply chain industry? <br>
• Which variables and features are important for Fraud Detection and Sales Prediction? <br>
• Which model is the best fit for Fraud Detection and Sales Prediction? <br>
These questions assist in defining the objectives: <br>
- To discover common dataset for Fraud and Sales prediction so that inter-relationships
between of features can be highlighted with respect to fraud and sales. <br>
- Obtain critical and comprehensive literature review for related research work. From
concrete sources like Journal Articles, ML Conferences, Books, Research Papers. <br>
- Perform EDA (Exploratory Data Analysis) for generating preliminary insights from the
dataset. <br>
- Setting up the hyper-parameters for essential Machine Learning model using
RandomizedSearchCV. <br>
- Feature engineering to obtain the impact of important features in the dataset. <br>
- Evaluate and validate results of ML models using metrics like Accuracy, F1, Recall Score
and RMSE, MAE values. <br>
- Setting up the services of AWS which will make the implementation of predictive
analysis easier and efficient. <br>
- Setting up AWS S3 permission and installation of essential packages for performing
cloud integration task. <br>


## Exploratory Data Analysis
### Heat Map
![](https://raw.githubusercontent.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/main/Screenshorts/HeatMap.PNG)
###  Most used method for Transaction
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/MostTransaction.PNG)
### Righest Fraud 
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/HighestFraudRegions.PNG)
### Total Sales
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/TotalSaleRegion.PNG)
### Total Loss in Revenue
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/MostLossRegion.PNG)


## Analysis and Findings
### Metrics of Tuned Classification Models
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/MetricsTunedModels.PNG)
### Computation time of tuned Classification Models
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/ComputationTimeTuned.PNG)
### Important Features
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/ImpFeaTuned.PNG)
### ROC Curve for Tuned Classification Models
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/ROCTuned.PNG)

### Metrics for Regression Models
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/MetricsReg.PNG)
### Comutaion time for Regression Models
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/TimeReg.PNG)
### RMSE v/s MAE plot and MSE Plot
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/RMSEMAEMSE.PNG)
### Predicted v/s Actual Result
![](https://github.com/tirth-pipalia/Assimilation-of-Machine-Learning-and-Cloud-Computing/blob/main/Screenshorts/Predicted.PNG)


### Conclusion
Random Forest is the best fit model for fraud prediction having Accuracy=98.332% Recall=65.969% F1=60.584% and AUC=77.668% when tuned and Training time =65.774s, Prediction Time =0.296s and tuning time=0.1302s. For Regression task Linear regression and Ridge Regression is the best fit model for sales
prediction based on RMSE and MAE error rate vales which for Linear Regression is 0.0014938985645114012 and 0.0005448947680783427. For ridge regression RMSE=0.001882263872915812 and MAE =0.0010036470043190342. <br>
## Technologies Used
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/1/1d/AmazonWebservices_Logo.svg" width=270>](https://aws.amazon.com/)
[<img target="_blank" src="http://ForTheBadge.com/images/badges/made-with-python.svg" width=270>](https://www.python.org/)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" width=270>](https://jupyter.org/)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width=270>](https://scikit-learn.org/stable/)
[<img target="_blank" src="https://static.javatpoint.com/tutorial/pandas/images/python-pandas.png" width=270>](https://pandas.pydata.org/)
[<img target="_blank" src="https://miro.medium.com/max/759/0*Xbg-CQX5W5NqXyG3.png" width=270>](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
[<img target="_blank" src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width=270>](https://numpy.org/)

## Bug / Future Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/tirth-pipalia/Django_REST_API_Travel_APP/issues/new)
by including your search query and the expected result. <br>

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/tirth-pipalia/Django_REST_API_Travel_APP/issues/new). 
Please include sample queries and their corresponding results. <br>


## License

[![Apache license](https://img.shields.io/badge/license-apache-blue?style=for-the-badge&logo=appveyor)](http://www.apache.org/licenses/LICENSE-2.0.txt)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at [Apache](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

