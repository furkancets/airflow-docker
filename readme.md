- curl -LfO 'https://airflow.apache.org/docs/apache-airflow/2.4.3/docker-compose.yaml'


- mkdir -p ./dags ./logs ./plugins


- echo -e "AIRFLOW_UID=$(id -u)" > .env


- docker compose up airflow-init


- docker-compose up


- Also, you can watch this video then you can create your airflow environment

https://www.youtube.com/watch?v=aTaytcxy2Ck&ab_channel=DatawithMarc
