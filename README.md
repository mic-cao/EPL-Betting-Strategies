# Directed Research: EPL Betting Strategies
**Author:** Michael Cao  
**Advisor:** Dr. James Booth, Cornell University

**Status:** In Progress

This repository contains the code and research findings for an ongoing research project focused on developing effective betting strategies for English Premier League (EPL) games. Supervised by Dr. Booth, the research involves extensive simulations and predictive modeling to explore profitable betting opportunities in soccer.

## Overview
The project is structured into three main components, each playing a pivotal role in developing and evaluating EPL betting strategies:

1. **EPL Prediction:** This phase encompasses the construction of predictive models using advanced machine learning algorithms. Leveraging features such as team performance metrics, historical match data, and contextual factors, we aim to forecast match outcomes with high accuracy.
   
   <p align="center">
   <img src="https://github.com/mic-cao/EPL-Betting-Strategies/blob/main/plots/plot1.png" alt="Histogram of Random Simulation Results" width="620">
   </p>

   The histogram above illustrates the results of a random simulation using games on week 26 of the 2023-24 season, emphasizing the challenges posed by bookmakers' vigorish on potential profits over the course of a season. Similar distribution is true for most matchweeks. This serves as motivation to develop robust betting strategies.

3. **EPL Betting:** Here, we dive into the realm of betting strategies, analyzing historical data and exploring various betting markets. Through rigorous experimentation and analysis, we aim to identify strategies that yield consistent profits over time, considering factors such as odds, market trends, and risk management.

   <p align="center">
   <img src="https://github.com/mic-cao/EPL-Betting-Strategies/blob/main/plots/plot3.png" alt="Simulation Results" width="750">
   </p>

   The plot shows the mean return on a $100 weekly bets over the first 30 weeks of the 2023-24 season, following a few simple betting strategies.

5. **Bets Optimization:** In this stage, we employ optimization techniques to enhance our betting strategies further. By formulating linear programming (LP) problems and conducting theoretical analyses, we aim to optimize betting weights to maximize expected profits while effectively managing risks. Theoretical demonstrations include uncovering biases in Opta’s predictions through maximum likelihood estimation.

   <p align="center">
   <img src="https://github.com/mic-cao/EPL-Betting-Strategies/blob/main/plots/plot4.png" alt="3D Plot of Theoretical Probabilities" width="450">
   </p>

   The 3D plot above showcases the theoretical probabilities of home win, draw, and away win, placed on a Dirichlet distribution. Understanding how these probabilities are distributed is crucial for formulating effective betting strategies.

## Key Features
- **Data Acquisition:** We procure historical odds and match data from reliable sources such as football-data.co.uk and Opta predictions. Rigorous data preprocessing ensures accuracy and reliability in our analysis.
- **Arbitrage Betting:** Exploring arbitrage opportunities by comparing bookmakers' odds enables us to capitalize on market inefficiencies and generate risk-free returns.
- **Predictive Modeling:** Our predictive models leverage sophisticated machine learning algorithms to estimate match outcomes and derive probabilities for various events, including win, lose, or draw. Continuous refinement and evaluation ensure high predictive accuracy.
- **Optimization Techniques:** We utilize mathematical optimization techniques, such as linear programming, to optimize betting strategies. By formulating and solving optimization problems, we aim to maximize expected profits while considering factors such as risk tolerance and market conditions.
- **Statistical Analysis:** Thorough statistical analysis is conducted to uncover patterns, trends, and biases in the data. Techniques such as maximum likelihood estimation and Dirichlet distribution analysis provide valuable insights into the underlying dynamics of EPL matches.

## Pending Publication
A paper based on the research findings is pending publication. Stay tuned for updates!
