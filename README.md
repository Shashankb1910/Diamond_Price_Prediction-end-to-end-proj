# This is my end to end project

# Diamond Price Prediction

```
git init
```

```
git add abc.txt
git add .
```
```
git commit -m "this is my first commit"
```

```

git pull

```

```
bash your_file_name.sh
```

```
python setup.py install
```

# another way you can mention -e . in your requirement file and you can run

```
pip install -r requirements.txt
```


## MLflow

[Documentation](https://mlflow.org/docs/latest/index.html)


##### local cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Shashankb1910/Diamond_Price_Prediction-end-to-end-proj.mlflow \
MLFLOW_TRACKING_USERNAME=Shashankb1910 \
MLFLOW_TRACKING_PASSWORD=40aea5dfc244c1f1f09fc9d0e267b9bf72ddcb38 \
python script.py

Run this to export as env variables:
#For cmd use "set" instead of export

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/Shashankb1910/Diamond_Price_Prediction-end-to-end-proj.mlflow 

export MLFLOW_TRACKING_USERNAME=Shashankb1910

export MLFLOW_TRACKING_PASSWORD=40aea5dfc244c1f1f09fc9d0e267b9bf72ddcb38

```


### DVC cmd
- dvc init
- dvc repro
- dvc dag

