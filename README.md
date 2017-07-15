### Interfaces

This post describes the different user interfaces of the environment
- Ambari server
- Yarn Ressource Manager
- Spark History Server
- Jupyter
- HUE


> Ambari server

Ambari provides an intuitive, easy-to-use Hadoop management web UI. It enables System Administrators to:
- Provision a Hadoop Cluster
- Central management for starting, stopping, and reconfiguring Hadoop services across the entire cluster
- Monitor a Hadoop Cluster

Ambari is accessible through this address: http://hadoop-m:8080


> Yarn Ressource Manager  

Ressource manager provide a web user interface to monitor hadoop job:
- progress of the job
- ressources used by the job
- status of the scheduler
- state of the jobs (FINISHED, SUCCEEDED, KILLED, FAILED)

Ressource Manager UI is accessible through this address: http://hadoop-w-0:8088


> Spark History Server  

Spark History Server provide a way to monitor Spark application. it displays useful information about application which includes:
- list of scheduler stages and tasks
- summary of RDD sizes and memory usage
- environmental information
- information about the running executors

Spark History Server is accessible through this address http://hadoop-m:18080


> Jupyter  

The Jupyter Notebook App allows editing and running notebook documents via a web browser. Our setup provides:
- Python 2.7 interface (inclusding Anaconda Analytics packages)
- Python 3
- Pyspark
- Terminal (shell console)

Jupyter is accessible through this address https://hadoop-w-3:9083


> HUE  

Hue is a Web interface for analyzing data with Hadoop. Hue is a suite of applications that provide web-based access to CDH components and a platform for building custom applications. It provides:
- SQL editors for Apache Hive
- Scheduling of jobs and workflows through an Apache Oozie Editor and Dashboard


HUE is accessible through this address: http://hadoop-w-3:8000


