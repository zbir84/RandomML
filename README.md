# RandomML
Lech's Machine Learning Sandbox

## Some commands worth noting to set up docker / MLflow

* `docker ps`
* `docker image ls`
* `docker build .`
* `docker build --build-arg VERSION=1.29.0 --tag mlflow_server:latest .`
* `docker-compose up -d`
* `docker-compose down`
* `docker logs container_name`
* `mlflow gc --backend-store-uri postgresql://<user_name>:<password>@0.0.0.0:5431`
