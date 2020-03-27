# Crunchbase

### Task:

*Predict the status (acquired, open or closed) of a company using Crunchbase data from Kaggle. Given the strong class imbalance, our model is unlikely to surpass the baseline. We want to tune towards recall in classes 0 and 2 (in the above order). We don't mind missing out on some companies, but when we classify, we want to be classify these classes correctly.*

### Key methods/challenges:

- Classification with imbalanced classes - under sampling, SMOTE, pipelines
- Creative-ish feature engineering

### Results:

- ~60% recall in classes 0 and 2.
- Will need more work to optimise!