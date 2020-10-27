# pyspark-learning

Notebooks 

## Requirements
You will need:
- [Github](https://desktop.github.com/)
- [Python](https://www.python.org/)
- [PySpark](https://spark.apache.org/)
- [Jupyter](https://jupyter.org/)

## Recomendations
You can also use [Docker](https://www.docker.com/get-started) to run:
- [Spark Server](https://hub.docker.com/r/gettyimages/spark/)
  Get docker image
  ```sh
  $ docker run --rm -it -p 4040:4040 gettyimages/spark bin/run-example SparkPi 10
  ```

  Get docker compose
  ```sh
  $ git clone https://github.com/gettyimages/docker-spark.git
  ```

  Change to _docker-sparck_ directory:
  ```sh
  $ cd docker-spark
  ```

  Run SparkPi, exec into a container:
  ```sh
  $ docker exec -it docker-spark_master_1 /bin/bash
  ```
  ```sh
  $ bin/run-example SparkPi 10
  ```
  
- [Jupyter Notebook](https://hub.docker.com/r/jupyter/pyspark-notebook)
  Get docker image
  ```sh
  $ docker pull jupyter/pyspark-notebook
  ```

## Note
This application is for learning purposes.

Enjoy : ] 
