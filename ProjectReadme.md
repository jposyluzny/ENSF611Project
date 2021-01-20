**Background on your code files**
- My project notebook is called ProjectNotebook.ipynb. It starts on the standard imports and mglearn project flow diagram. Next:
- a function is defined for scoring the completed models.
- the CSV was imported and split into X and y after being cleaned
- the data is visualized in countplots, a heatmap, and a histogram
- I decided to skip the initial cross-validation scoring step, as I wanted to see how each model would perform with optimal parameters
- The unscaled models were grid searched in order of Bayesian Ridge, RandomForest, and GradientBoosting. Immediately after each were trained, they were fit and scored
- The scaled models were grid searched in order of LinearSVR and K Nearest Neighbors. Immediately after each were trained, they were fit and scored
- Then, each of the models were listed with their optimal parameters, training data MSE, and testing data MSE
- The results of the best model were visualized
- Conclusion and Reflection follow at the end

**How to run your code, guide to install any additional packages**
- The code should be run in order, and should just fire properly. There are no additional packages to install, and all imports are standard for 611. Be warned, however, that some of the grid searches take a very long time.

**Results, interpretation and reflection**
- Results, interpretation, and reflection are at the end of ProjectNotebook.
