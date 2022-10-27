# Portfolio_website
Data science portfolio by Jonathan Griffiths 


## Project 1 - Waste-water sewage pumping station electricity consumption forecasting

  ### Overview

  **Project type:** Professional, data science
  
  **Institute:** Maiple
  
  **Collaborators:** UK Utility company
  
  **Dates:** Jan - April 2020
  
  **Languages:** Python
  
  **Tools:** AWS, Sagemaker, Sci-kit learn, GluonTS, MxNet

  ### Description
  - Feasbility study to assess ability to use AI models to predict energy consumption of Wastewater pumping stations based on local rainfall forecasts. 
  - 129 stations in various locations across the UK with 2 years of data from April 2018 to March 2020 was created.
  - Stations were placed in 3 groups based on rainfall correlation using the Pearson correlation score. 
  - A DeepAR model implementation from the GluonTS deep learning time series forecasting was used to create a model for each group of stations.
  - The models were trained using Amazon Sagemaker in AWS and hyperparamter tuning was performed to improve model performance. 
  - Acceptable results for 90% of the stations with a correlation score greater than 0.3. The remaining 10% of the stations were not able to be accurately forecasted, data for these stations was generally found to be of poor quality.
  

## Project 2 - Optical Character Recognition (OCR) for receipt digitisation 

  ### Overview
  
  **Project type:** University, data science
  
  **Institute:** Data ScienceTech Institute
  
  **Collaborators:** 
  
  **Dates:** May - November 2021
  
  **Languages:** Python
  
  **Tools:** AWS, OpenCV, Pytorch, DarkNet, YOLO, GCP OCR, AWS Rekognition, Docker
    
  ### Description
  - Masters end of year group project to create a python library for using AI for receipt digitalisation. This task used a combination of OCR, Computer Vision and NLP in order to identify and extract the key information on a variety of receipts from restaurants, shops, supermarkets etc. 
  - The goal of the project was to identify the establishment address, date and the total amount spent on the receipt.
  - A data processing pipeline was contructed using AWS to build and annotate a dataset X of receipts collected by team members and the project supervisor. 
  - The receipts were digitalised using an OCR tool provided by Google Cloud via an api, recipts were then manually annotated by team members with an image annotation tool. 
  - The models used for training include YOLOv4 and a custom implementation of the Convolutional Universal Text Information Extractor (CUTIE) model in Pytorch
  - The results 

## Project 3 - Hospital electricity and heat consumption forecasting 

  ### Overview
  **Project type:** Professional, data science
  
  **Institute:** Maiple
  
  **Collaborators:** UK utility company
  
  **Dates:** November 2021 - March 2022
  
  **Languages:** Python
  
  **Tools:** AWS, AWS EC2, AWS Sagemaker, AWS Lambda, Docker, MLOPS
    
  ### Description
    - Demand-side energy forecasting of UK hospital electricity consumption to explore possibility of using AI time series forecasting models for campus buildings to participate in flexible energy contracts offered by DNOs (Distribution Network Operators) to reduce pressure on the electricity network during peak operating hours.
  - Project in collaboration with Cardiff University’s Centre for Integrated Renewable Energy Generation (CIREGS) team as part of the FlexisApp initiative.
  - This project follows the use of machine learning and deep learning tools to forecast electricity and heat demand over an 11 day period. The experiments were carried out in AWS using EC2 instances as well as Amazon Sagemaker. The Sci-kit learn and GluonTS Python libraries were used to train the models. 
  - The models tested included SARIMA, ETS, Holt-Winters, Random Forest and XGBoost regressors, DeepAR and Multi-Layer Perceptron
  - The best model was found to be the Random Forest regression model from sci-kit learn which was tuned using GridSearch.


## Project 4 - School electricity consumption forecasting 

  ### Overview

  **Project type:** Professional, data science
  
  **Institute:** Maiple
  
  **Collaborators:** FLEXISApp, CIREGS
  
  **Dates:** April 2022 - May 2022
  
  **Languages:** Python
  
  **Tools:** AWS 
    
  ### Description
  - Energy forecasting of UK school using AI modelling. Feasibility study, part of FLEXISApp project to find baseline forecasting accuracy for site to be used as a potential use case for participation in flexible power contracts. 
  - The original dataset contained 3 years of data ranging from June 2016 to February 2021.  A time series analysis was performed on the dataset and the data was then trained with models using traditional, ML and DL forecasting techniques. 
  - Covariate data including weather forecast data, seasonal features as well as school closure information was added to the dataset to improve model performance. 
  - All models were trained using default hyper parameters with no hyper parameter tuning. 
  - The best model was found to be the Random Forest Regression model. 

## Project 5 - Electricity consumption forecasting in R 

### Overview

  **Project type:** Study, data science
  
  **Institute:** Data ScienceTech Institute
  
  **Collaborators:** -
  
  **Dates:** October 2021
  
  **Languages:** R
  
  **Tools:** -
    
### Description


## Project 6 - Flexible power application API development 

  ### Overview

  **Project type:** Professional, data engineering
  
  **Institute:** Maiple
  
  **Collaborators:** FLEXISApp, CIREGS
  
  **Dates:** May 2022 - present 
  
  **Languages:** Python
  
  **Tools:** AWS, SQL, AWS Lambda
    
  ### Description
  
  - Development of flexible power application in AWS for participation in flexible energy contracts.
  - AWS architecture design and implementation
  - Python API to retrieve 3rd party API weather forecast data 
  - Python library with ETL, AI model training, serving and monitoring functionalities
  - Python API for PostgreSQL based time series database TimescaleDB
  - Python GraphQL API for DynamoDB using AWS AppSync
  - Automated CI/CD pipeline using AWS CodePipeline, CodeBuild, CodeDeploy and AWS Cloud Development Kit (CDK)



