# Pairs Trading Project

## Introduction
This project focuses on implementing a pairs trading strategy using a combination of statistical tests, specifically the Dickey-Fuller test and Monte Carlo simulation for critical value generation. The aim is to identify pairs of stocks that are cointegrated and then develop a daily trading strategy based on observed signals.

## Features
- Simulation of Dickey-Fuller test with Monte Carlo simulation to obtain critical values.
- Simulation of cointegration with Monte Carlo simulation to obtain critical values.
- Identification of pairs of stocks that are most cointegrated.
- Implementation of a daily trading strategy:
  - Calculation of signal z̃t using adjusted prices at close.
  - Execution of trades the next morning at adjusted prices at open.

## Notebooks
- `pairs_trading.ipynb`: Main notebook containing the pairs trading strategy implementation.
- `pickles_generations.ipynb`: Notebook for generating critical values using Monte Carlo simulation. Note: This process is time-consuming, and the critical values are stored in the pickles file for convenience.

## Files
- `critical_values.pickle`: Pickle file containing pre-generated critical values obtained from Monte Carlo simulation.
- Other necessary files such as data files, helper functions, etc.
