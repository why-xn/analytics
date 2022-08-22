**Build PySpark Container**
```
docker build -t whyxn/apache.spark-py:v3.2.1 -f Dockerfile.spark .
```

**Build Jupyter Notebook Container**
```
docker build -t whyxn/jupyter-notebook.spark.3.2.1:v3.0 -f Dockerfile.spark .
```