# MLflow logging API for Diabetes ML prediction
The example illustrates illustrates how to use the MLflow logging API to start an MLflow run and log the model, model parameters, evaluation metrics, and other run artifacts to the run. The easiest way to get started using MLflow tracking with Python is to use the MLflow autolog() API. If you need more control over the metrics logged for each training run, or want to log additional artifacts such as tables or plots, you can use the mlflow.log_metric() and mlflow.log_artifact() APIs demonstrated in this notebook.

- from Micorsoft Azure Databricks open the notebook
- install the mlflow library from PyPI 
```
pip install mlflow
```
Then, activate this app's virtualenv: virtualenv -p python3 venv  # For Python 3
```
