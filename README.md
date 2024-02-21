# MLflow logging API for Diabetes ML prediction
The example illustrates how to use the MLflow logging API to start an MLflow run and log the model, model parameters, evaluation metrics, and other run artifacts to the run. The easiest way to get started using MLflow tracking with Python is to use the MLflow autolog() API. If you need more control over the metrics logged for each training run, or want to log additional artifacts such as tables or plots, you can use the mlflow.log_metric() and mlflow.log_artifact() APIs demonstrated in this notebook.
## Steps for the implementation 
- Sign in to the Azure cloud account with administrative privileges.
- Create Azure Databricks workspace
- from Microsoft Azure Databricks open the notebook
- install the MLflow library from PyPI 
```
pip install mlflow
```

## Images
![Imgur](https://imgur.com/fTmp5sA.png)
![Imgur](https://imgur.com/k2P9w74.png)
