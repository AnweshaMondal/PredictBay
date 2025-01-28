# PredictBay

This project implements a Housing Price Prediction model using Multiple Linear Regression. The model predicts the price of houses based on various factors such as average area income, house age, number of rooms, number of bedrooms, and area population.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates how to use Multiple Linear Regression to predict housing prices. It includes data preprocessing, model training, and evaluation.

The model uses multiple features to predict the price of a house, including:
- **Avg. Area Income**: The average income of the area where the house is located.
- **Avg. Area House Age**: The average age of the houses in the area.
- **Avg. Area Number of Rooms**: The average number of rooms in houses in the area.
- **Avg. Area Number of Bedrooms**: The average number of bedrooms in houses in the area.
- **Area Population**: The population of the area.
- **Price**: The price of the house (target variable).

## Dataset

The dataset used in this project contains the following columns:

| Column Name                       | Description                                      |
|-----------------------------------|--------------------------------------------------|
| Avg. Area Income                  | The average income in the area                   |
| Avg. Area House Age               | The average age of houses in the area            |
| Avg. Area Number of Rooms         | The average number of rooms in houses            |
| Avg. Area Number of Bedrooms      | The average number of bedrooms in houses         |
| Area Population                   | The population of the area                       |
| Price                             | The price of the house (target variable)         |

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/housing-price-prediction.git
cd housing-price-prediction
pip install -r requirements.txt
