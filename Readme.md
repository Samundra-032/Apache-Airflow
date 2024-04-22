# Installing Apache Airflow

- make **dockerfile**
- right click on the dockerfile and click -> _build image..._

- make **docker-compose.yml**
- right click on the docker-compose.yml file and click -> _Compose up_

### now open docker and see the container and volume allocated to it

#### To access Apache airflow

- localhost:8080
- username: admin
- password: on vscode where you are writing the dockerfile and docker-compose file it will create a folder search for **standalone_admin_password.txt** the password is inside it

#### now you have access to Airflow interface

## to develope and schedule an airflow

- create a **dags** folder inside the newly created folder i.e here airflow
- inside **dags** create .py file and create a schedule inside it

### it will take some time to get load inside the web interface

- now you can automate or manually start any task
- check the logs to verify

### to terminate all

- choose **docker-compose.yml** file and right click and click to **compose down**
