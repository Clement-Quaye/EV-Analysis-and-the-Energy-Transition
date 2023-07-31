# EV-Analysis-and-the-Energy-Transition
Predictive Analysis of EV Charging Behaviour: Implications for Smart Grid Design
This repository contains the code, data, and results of a dissertation project focused on the predictive analysis of Electric Vehicle (EV) charging behavior and its implications for smart grid design. The project is part of a broader initiative to understand and facilitate the energy transition towards more sustainable and efficient systems.

Table of Contents
Project Overview
Data Description
Methodology
Models Used
Results
Implications for Smart Grids
Conclusion
References

Project Overview <a name="project-overview"></a>
The project aims to analyze the charging behavior of EVs using real-world data from 37 domestic charging stations. The goal is to develop predictive models that can forecast power consumption patterns, providing valuable insights for the design and management of smart grids.

Data Description <a name="data-description"></a>
The dataset used in this project was collected from 37 domestic EV charging stations over a period from 1st February 2023 to 15th June 2023. The dataset includes several features such as power, timestamp, voltage, frequency, charge energy, and others. The primary feature used for prediction in this project is the power feature, making this a univariate analysis.

Methodology <a name="methodology"></a>
The methodology involves several steps including data preprocessing, model training, and evaluation. The data preprocessing step involves resampling the data to 15-minute intervals, handling missing values, and scaling the data. Three different models, namely Random Forest, Decision Tree, and XGBoost, were trained and evaluated using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) metrics.

Models Used <a name="models-used"></a>
The models used in this project include:

Random Forest: An ensemble method that uses multiple decision trees and averages their predictions to enhance accuracy and robustness.
Decision Tree: A single tree structure that can be visualized and interpreted but may require pruning to prevent overfitting.
XGBoost: An advanced boosting algorithm that combines multiple weak learners, optimized for efficiency and flexibility.
Each model was optimized using specific techniques such as hyperparameter tuning, pruning, and regularization.

Results <a name="results"></a>
The results section contains the RMSE and MAE values for each model, along with visualizations of the actual vs. predicted power consumption. The Random Forest model emerged as the most suitable for this specific dataset and prediction task.

Implications for Smart Grids <a name="implications-for-smart-grids"></a>
The findings of this project have significant implications for the design and management of smart grids. By understanding and predicting EV charging behavior, grid operators can better manage load, optimize energy distribution, and plan for infrastructure upgrades.

Conclusion <a name="conclusion"></a>
This project contributes to the broader goal of facilitating the energy transition by providing insights into EV charging behavior and its implications for smart grid design. The predictive models developed in this project can be further refined and used in real-world applications to enhance the efficiency and sustainability of energy systems.

References <a name="references"></a>
The references section will contain citations to relevant literature and resources used in the project
