The environment has an Apache Airflow application running as a Docker Container. You can view the status using docker ps{{execute}}.

The commands used to launch the container was:

- docker pull puckel/docker-airflow
- docker run --name airflow -d -p 8080:8080 puckel/docker-airflow

All plugins and configurations get persisted to the host at /root/airflow. Port 8080 opens the web dashboard.

#### Load Dashboard

You can load the Airflow interfaced via the following URL https://[[HOST_SUBDOMAIN]]-8080-[[KATACODA_HOST]].environments.katacoda.com/

