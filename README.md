# Directed Research: EPL Betting Strategies
**Author:** Michael Cao  
**Advisor:** Dr. Jim Booth, Cornell University

**Status:** In Progress

This repository contains the code and research findings for an ongoing research project focused on developing effective betting strategies for English Premier League (EPL) games. Supervised by Dr. Booth, the research involves extensive simulations and predictive modeling to explore profitable betting opportunities in soccer.

## Overview
The project is divided into three main components, each serving a crucial role in the development and evaluation of EPL betting strategies:

1. **EPL Prediction:** This phase involves building predictive models using classification algorithms to forecast match outcomes. Various features such as team performance metrics, historical match data, and contextual factors are considered to train the models.

2. **EPL Betting:** Here, we delve into the world of betting strategies, investigating different approaches to maximize profits. We analyze historical data, assess various betting markets, and experiment with different staking plans to identify strategies with consistent returns.

3. **Bets Optimization:** In this stage, optimization techniques are employed to enhance our betting strategies further. By formulating linear programming (LP) problems and theoretical analysis, we aim to optimize betting weights, considering factors such as risk tolerance, odds, and expected returns. Theoretical demonstrations include the presence of bias in Opta’s predictions through maximum likelihood estimation and Dirichlet distribution analysis.

## Key Features
- **Data Acquisition:** Historical odds and match data are obtained from reliable sources, such as football-data.co.uk and Opta predictions. We meticulously clean and preprocess the data to ensure accuracy and reliability in our analysis.
- **Arbitrage Betting:** We explore arbitrage opportunities by comparing bookmakers' odds and identifying instances where differences in odds allow for risk-free returns. This strategy is crucial in capitalizing on market inefficiencies.
- **Predictive Modeling:** Our predictive models leverage machine learning algorithms to estimate match outcomes and derive probabilities for different events, such as win, lose, or draw. These models are continuously refined and evaluated to improve accuracy.
- **Optimization Techniques:** We utilize mathematical optimization techniques, such as linear programming, to optimize our betting strategies. By formulating and solving optimization problems, we aim to maximize expected profits while managing risks effectively.
- **Statistical Analysis:** We conduct thorough statistical analysis to identify patterns, trends, and biases in the data. Techniques such as maximum likelihood estimation and Dirichlet distribution analysis are employed to gain insights into the underlying dynamics of EPL matches.

## Usage
1. **EPL Prediction:** Run the `epl_prediction.Rmd` script to build and evaluate predictive models. This script generates insights into match outcomes and provides probabilities for different events.
2. **EPL Betting:** Execute the `epl_betting.Rmd` script to explore various betting strategies and analyze their performance. This script helps in identifying profitable betting opportunities and assessing the effectiveness of different staking plans.
3. **Bets Optimization:** Utilize the `bets_optimization.Rmd` script to formulate and solve LP problems for optimizing betting weights. This script aids in maximizing expected profits while considering factors such as risk tolerance and market conditions.

## Requirements
- R programming language
- Required R packages: `lpSolve`, `plotly`, `gtools`, `data.table`

## Pending Publication
A paper based on the research findings is pending publication. Stay tuned for updates!
