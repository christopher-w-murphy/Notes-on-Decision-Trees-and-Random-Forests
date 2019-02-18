# Notes on Decision Trees and Random Forests

## Decision Trees and Random Forests
These are my notes for the [Insight](https://www.insightdata.ai/) interview prep workshop I led on Random Forests. They mostly are based on chapters 6 and 7 of *Hands-On Machine Learning with Scikit-Learn and TensorFlow* by Aur&eacute;lien G&eacute;ron, https://github.com/ageron/handson-ml, with the emphasis of topics and some additional content coming from the Insight Interview Prep Checklist. 

The structure of the notebook is as follows:

- Decision Trees and Random Forests
  - Setup
- Decision Trees
  - Training and Visualizing a Decision Tree
  - Making Predictions
    - Predicting classes and class probabilities
    - The CART training algorithm
  - Regularization Hyperparameters
  - Regression
- Ensemble Learning and Random Forests
  - Voting Classifiers
  - Bagging and Pasting
  - Random Forests
    - Feature importance
  - Boosting
    - Gradient boosting
  - Exercise

Note that MathJax is not working properly in the Jupyter Notebook uploaded to GitHub, as opposed to on my computer, so the equations are not being visualized correctly. One option is to paste the link to the notebook into http://nbviewer.jupyter.org

## Advanced Topics
Frequently comes up during interviews
- Class Imbalance

Good to know of even if you don't use it
- LightGBM

To Do:
- Prediction Intervals
- XGBoost
