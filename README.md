# Kidney-Disease-Classification


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/danfranc0/Kidney-Disease-Classification.git
```


### STEP 1- Create a conda environment

```bash
conda create -n cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 2- Install the requirements
```bash
pip install -r requirements.txt
```


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/danfranc0/Kidney-Disease-Classification.mlflow \
MLFLOW_TRACKING_USERNAME=danfranc0 \
MLFLOW_TRACKING_PASSWORD=2b7d0c976d6de2cbd9d3cbf08800716950255c81 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/danfranc0/Kidney-Disease-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=danfranc0

export MLFLOW_TRACKING_PASSWORD=2b7d0c976d6de2cbd9d3cbf08800716950255c81

```