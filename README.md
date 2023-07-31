# Predictive Analysis of EV Charging Behaviour: Implications for Smart Grid Design

## Table of Contents
1. [Introduction](#introduction)
2. [Context and Relevance](#context-and-relevance)
3. [Methodology](#methodology)
4. [Models Used](#models-used)
5. [Results](#results)
6. [Implication on Smart Grids](#implication-on-smart-grids)
7. [Conclusion](#conclusion)
8. [Installation and Usage](#installation-and-usage)
9. [License](#license)

## Introduction
This repository contains the code and data for the dissertation project focusing on the predictive analysis of Electric Vehicle (EV) charging behavior. The project aims to understand and model the charging patterns of EVs and their implications for smart grid design.

## Context and Relevance
The transition to renewable energy and the growth of EVs are central to the global energy transition. Understanding EV charging behavior is vital for:
- **Grid Stability:** Ensuring that the grid can handle the increased load from EVs.
- **Energy Efficiency:** Optimizing charging times to utilize renewable energy sources.
- **Infrastructure Planning:** Designing charging infrastructure that meets the needs of EV users.

## Methodology
The methodology includes:
- **Data Collection:** From 37 EV Domestic Charging stations, collected from 1-Feb-2023 to 15-June-2023.
- **Data Preprocessing:** Including resampling, null value handling, scaling, and splitting.
- **Time Series Analysis:** Using a univariate model with the power feature.

## Models Used
Three models were utilized:
1. **Random Forest:** Ensemble of decision trees.
2. **Decision Tree:** Tree-like graph model.
3. **XGBoost:** Optimized gradient boosting algorithm.

For detailed information on the architecture, inputs, and outputs of each model, refer to the [Models Used section](#models-used).

## Results
The results include RMSE and MAE for each model, along with visualizations. The comparative analysis of the models is provided, highlighting their performance and relevance.

## Implication on Smart Grids
The findings have significant implications for smart grid design, including:
- **Demand Response Management:** Enabling more responsive and flexible grid operations.
- **Integration with Renewables:** Facilitating the integration of renewable energy sources.
- **Policy and Regulation:** Informing policy decisions related to EV charging infrastructure.

## Conclusion
The project provides valuable insights into EV charging behavior and its implications for smart grid design, contributing to the broader energy transition goals.

## Installation and Usage
Instructions for setting up the environment and running the code are provided in the [Installation Guide](INSTALLATION.md).

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
