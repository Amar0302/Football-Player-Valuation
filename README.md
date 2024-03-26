# Understanding Football Player Valuation Through Quantitative Analysis

## Overview

This repository hosts an extensive suite of Jupyter notebooks for the analysis and valuation of football players, centered around the utilisation of the WyScout datasets. This project aims to bridge advanced data science and machine learning methodologies with the intricate world of football analytics. It is tailored to unveil how various factors—ranging from player popularity and on-field positioning to performance-based and beyond-performance metrics—play a pivotal role in determining a player's market value. At the core of our investigation is the prediction of player positions based on performance metrics, facilitated through the comprehensive data provided by WyScout. This initiative is crafted to shed light on the multifaceted aspects of player valuation, offering nuanced insights into the dynamics that influence player positioning and valuation in the realm of professional football.

## Project Structure

The project is organized into several key components, each focusing on a specific aspect of player analysis and valuation:

- **Neural Network Models**: Implementation of neural networks to predict player position through performance based metrics.
- **Player Popularity Analysis**: Examination of players' popularity through web scraping and data analysis.
- **Market Valuation Models**: Estimation of players' market values based on all analysed metrics. 

### Notebooks Description

1. **NeuralNetwork2.ipynb**
   - Focus: Utilizes neural network models to predict player positions based on WyScout performance metrics.
   - Technologies: TensorFlow, Keras, Scikit-learn
   - Data: Seasons 2018-2019 to 2022-2023 performance data.

2. **PlayerPopularityAnalysis.ipynb**
   - Focus: Analyzes player popularity through Google API webscraping techniques.
   - Methodology: Data aggregation from various online sources and analysis of social media trends.

3. **PlayerPopularityGoogleScrape.ipynb**
   - Focus: This code fetches and records the Google search results count for a list of football players from the WyScout dataset.
   - Tools: Google Custom Search JSON API

4. **PlayerPositioningNN.ipynb**
   - Focus: Applies neural networks to analyze and predict player positioning on the field.
   - Approach: Data preprocessing, neural network training, and position prediction.

5. **Players_Market_Valuation.ipynb**
   - Focus: Estimates players' market values based on performance data and statistical models.
   - Techniques: Regression analysis, data visualisation.

6. **Updated_Market_Value_Analysis.ipynb**
   - Focus: Analysing and updating the market values of football players using both performance-based and non-performance-based metrics.
   - Highlights: Incorporates recent market changes, transfer data, and performance indicators.

## Project Goals

The primary objectives of this project are to:

- **Enhance Understanding**: Deepen the understanding of factors influencing a football player's market value.
- **Predictive Modeling**: Develop models that can predict player position through metric data.
- **Data-Driven Insights**: Provide clubs, analysts, and fans with data-driven insights for informed decision-making.

## Data Sources

This project leverages a wide array of data sources, including:

- Performance data from multiple seasons through WyScout
- Google search count data through Google Custom Search JSON API.

## Technologies

The project utilizes several technologies and libraries, notably:

- **Data Analysis**: Pandas, NumPy
- **Machine Learning**: Scikit-learn, TensorFlow, Keras
- **Data Visualization**: Matplotlib, Seaborn
- **Web Scraping**: Google Custom Search JSON API.

## Getting Started

To get started with this project:

1. **Clone the repository**: Use `git clone` to download the project.
2. **Install dependencies**: Ensure you have Python installed and proceed to install the required libraries using `pip install -r requirements.txt`.
3. **Explore the notebooks**: Each notebook is self-contained and includes comments and explanations to guide you through the analysis.

## Contribution

Contributions to the project are welcome! If you have suggestions for improvements or new features, please feel free to fork the repository, make changes, and submit a pull request.

## Copyright

This project is licensed under the MIT License - see the LICENSE file for details.
