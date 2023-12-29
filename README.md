# Kidney-Disease-Classification


# How to run?
### STEPS:

Clone the repository

bash
https://github.com/Anirudh-Kavle/ML-project
### STEP 01- Create a conda environment after opening the repository

bash
conda create -n cnncls python=3.8 -y


bash
conda activate cnncls



### STEP 02- install the requirements
bash
pip install -r requirements.txt


bash
# Finally run the following command
python app.py


Now,
bash
open up you local host and port







## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Anirudh-Kavle/ML-project.mlflow \
MLFLOW_TRACKING_USERNAME=Anirudh-Kavle \
MLFLOW_TRACKING_PASSWORD=ec1b6e4651dec3b5e7d2925d8f1399d6885ad183 \
python script.py

Run this to export as env variables:

bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Anirudh-Kavle/ML-project.mlflow

export MLFLOW_TRACKING_USERNAME=Anirudh-Kavle 

export MLFLOW_TRACKING_PASSWORD=ec1b6e4651dec3b5e7d2925d8f1399d6885ad183




### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag



