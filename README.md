# mlops-with-dvc-mlflow-dagshub

Local setup:
```bash
mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 5000
```

DagsHub setup:  
'src/mlflow-credentials.py' file should be created in the root directory with the MLFLOW_TRACKING_USERNAME and MLFLOW_TRACKING_PASSWORD, and set MLFLOW_TRACKING_URI in params.yaml file.
```bash
MLFLOW_TRACKING_URI=TRACKING_URI \
MLFLOW_TRACKING_USERNAME=USER_NAME \
MLFLOW_TRACKING_PASSWORD= USE_YOUR_KEY \
```