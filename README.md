# cancer-detection

import dagshub
dagshub.init(repo_owner='Aly201', repo_name='cancer-detection', mlflow=True)

import mlflow
with mlflow.start_run():
mlflow.log_param('parameter name', 'value')
mlflow.log_metric('metric name', 1)
