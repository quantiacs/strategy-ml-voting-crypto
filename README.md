# Machine Learning with a Voting Classifier: Retraining your Model

This trading strategy is designed for the [Quantiacs](https://quantiacs.com/contest) platform, which hosts competitions
for trading algorithms. Detailed information about the competitions is available on
the [official Quantiacs website](https://quantiacs.com/contest).

## How to Run the Strategy

### In an Online Environment

The strategy can be executed in an online environment using Jupiter or JupiterLab on
the [Quantiacs personal dashboard](https://quantiacs.com/personalpage/homepage). To do this, clone the template in your
personal account.

### In a Local Environment

To run the strategy locally, you need to install the [Quantiacs Toolbox](https://github.com/quantiacs/toolbox).

## Strategy Overview

The Jupyter Notebook presents a strategy for forecasting financial time series using machine learning, specifically
tailored for the Quantiacs platform. This strategy is focused on the retraining of a model to adapt to new data on a
rolling basis, using BTC Futures Contracts as the primary asset. The core of the model is a Voting Classifier that
combines Ridge Classifiers and Stochastic Gradient Descent Classifiers from the scikit-learn library. The strategy
employs a specialized version of the Quantiacs backtester, optimized for scenarios where models need frequent
retraining.
