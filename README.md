# Chest-Disease-Classification-from-Chest-CT-Scan-Image

## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 







## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```

# MLFLOW Dags Hub Connection URI

```bash
 
MLFLOW_TRACKING_URI=https://dagshub.com/JunaidARahat/MLFLOW-Demo-Experiement.mlflow
MLFLOW_TRACKING_USERNAME=JunaidARahat \
MLFLOW_TRACKING_PASSWORD=ae3ac0903c1cf1d1779e5037cb9b17f98f664ebb  \
python script.py

```

# Run from bash Terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/JunaidARahat/MLFLOW-Demo-Experiement.mlflow
export MLFLOW_TRACKING_USERNAME=JunaidARahat

export MLFLOW_TRACKING_PASSWORD=ae3ac0903c1cf1d1779e5037cb9b17f98f664ebb

```