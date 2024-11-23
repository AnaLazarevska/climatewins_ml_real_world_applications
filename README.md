# ClimateWins Machine Learning Project - Real-world Applicaitons
A project that is continuation of the climatewins_machine_learning project, exploring real-world machine learning applications, including unsupervised learning, deep learning, and computer vision.

## Project Overview
This project leverages machine learning techniques to analyze historical weather data and satellite imagery to identify emerging weather patterns, predict future climate trends, and assess the impact of climate change on European regions. By applying advanced algorithms like Random Forests, CNNs, RNNs, and GANs, the project aims to provide valuable insights for climate change mitigation and adaptation strategies.

Note: The project was developed for the purposes of the Career Foundry's Data Analytics program.

## Business Questions
- Identify weather patterns outside the regional norm in Europe.
- Determine if unusual weather patterns are increasing.
- Generate possibilities for future weather conditions over the next 25 to 50 years based on current trends.
- Determine the safest places for people to live in Europe over the next 25 to 50 years.

- ## Data Overview
The dataset used in this project is sourced from the European Climate Assessment & Data Set project and contains historical weather observations from 18 different weather stations across Europe. 
The data includes variables such as temperature, wind speed, snow, global radiation, and more, spanning from the late 1800s to 2022.

- [ClimateWins Data](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv)

Citation: “I acknowledge the data providers in the ECA&D project. Klein Tank, A.M.G. and Coauthors, 2002. Daily dataset of 20th-century surface air temperature and precipitation series for the European Climate Assessment. Int. J. of Climatol., 22, 1441-1453. Data and metadata available at https://www.ecad.eu, Accessed via CareerFoundy on <15/10/2024>. 

Aditionally, [Multi-class Weather Dataset](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset) was used for training the model.

Note: Due to data limitation, the original and prepared datasets, as well as the some visualisations could not be uploaded to this repository.

## Tools and Technologies

- Python: The primary programming language used for data analysis and visualisation.
- Jupyter Notebook: A popular environment for interactive data science.
- pandas: A library for data manipulation and analysis.
- SciPy: Scientific computing library for optimization, integration, and signal processing.
- TensorFlow: Deep learning framework for building and training neural networks.
- Keras: High-level API for TensorFlow, simplifying the process of building and training models.
- scikit-learn: A machine learning library with a wide range of algorithms.
- scikeras: Integrates scikit-learn and Keras, allowing seamless use of Keras models within scikit-learn pipelines.
- BayesianOptimization: A library for optimizing hyperparameters of machine learning models.
- Matplotlib: A library for creating various plots and visualisations.
