# Airflow

## Install
```
helm repo add apache-airflow https://airflow.apache.org
helm upgrade --install airflow apache-airflow/airflow --namespace airflow --create-namespace
```

## DAG
/opt/airflow/dags/