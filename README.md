# youtube-sentiment-insights

conda create -n youtube python=3.11 -y

conda activate youtube

pip install -r requirements.txt


## DVC

dvc init

dvc repro

dvc dag



## AWS

aws configure

## MLFLOW

 mlflow server   --host 0.0.0.0   --port 5000   --default-artifact-root s3://arham-mlflow-bucket

### Json data demo in postman

http://localhost:5000/predict

```python
{
    "comments": ["This video is awsome! I loved a lot", "Very bad explanation. poor video"]
}
```



chrome://extensions