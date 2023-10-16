# mlops-with-dvc-mlflow-dagshub

Thanks to this repo:

https://github.com/c17hawke/simple-dvc-demo


Local setup:

```bash
mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 5000
```