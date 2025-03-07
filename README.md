# Climate Change Prediction Using Machine Learning

## Project Overview
This project uses machine learning techniques to predict the consequences of climate change in Europe. It's part of an initiative by ClimateWins, a European nonprofit organization, to leverage data analysis for climate change understanding and prediction.

## Objectives
- Predict extreme weather events in Europe using machine learning models
- Analyze temperature trends from European weather stations over the past century
- Identify specific weather patterns that may precede favorable or dangerous conditions
- Identify weather patterns outside the regional norm in Europe.
- Determine if unusual weather patterns are increasing.
- Generate possibilities for future weather conditions over the next 25 to 50 years based on current trends.
- Determine the safest places for people to live in Europe over the next 25 to 50 years.

## Data Source
- [European Climate Assessment & Dataset project](https://www.ecad.eu/)
- 18 weather stations across Europe
- Data range: Late 1800s to 2022
- Daily recordings of temperature, wind speed, snow, global radiation, etc.
- [Dataset](https://s3.amazonaws.com/coach-courses-us/public/courses/da-spec-ml/Scripts/A1/Dataset-weather-prediction-dataset-processed.csv)
- [GAN Weather Image Dataset (Kaggle)](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset)

## Methods Used
- Gradient Descent for data optimization
- K-Nearest Neighbors (KNN)
- Decision Trees
- Artificial Neural Networks (ANN)
- Convolution Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Random Forests
- GANs

## Key Findings
- KNN model showed the best performance among the tested models
- Temperature extremes have generally increased over time in the studied locations
- Potential overfitting identified in some station data (e.g., Sonnblick)
- Utilizing multiple learning methods (e.g important features from Random Forests & time series prediction with RNNs) can help develop research

## Future Steps
- Refine and optimize the KNN model
- Address potential overfitting issues
- Expand analysis to more diverse geographical locations
- Develop a user-friendly interface for stakeholders
- Validate models with recent climate data
- Incorporate additional climate variables

## Tools Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Keras
- Scikit Learn

## Contributors
Kirsten Currie

## YouTube Presentation
[Video Link](https://youtu.be/iBdLUct-76k)


## Acknowledgments
- ClimateWins for project initiation and support
- European Climate Assessment & Dataset project for providing the data

