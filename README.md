# Introduction
This Project was created using Rony Framework by A3 Data. Rony has a standard folder structure (including virtual environment), but some folders with code were not used in this project. I only used the codes that are in the "kubernetes", "dags" and "edc_mod4_exercise_igti_env/docker" folders. To find more information about Rony, go to https://github.com/A3Data/rony.
# Description
I’ve divided this project into three small explanations that follow below:
### About Docker
In this project I’ve performed practices with Docker using  commands  like “docker ps -a”,  “docker images”,” docker run -p...”, “docker stop..”, “docker run -it ...”, etc . Likewise I’ve built an API to pack in a Docker container(fastapi and uvicorn) and a Python Job using DockerFiles. At the end I’ve uploaded an image to the Docker Hub website and  I’ve created a private repository in AWS ECR.
### About Kubernetes
To contínuos in this Project, I’ve worked locally with Kind and remotely in AWS with EKS and managing cluster with Eksctl. In GCP I’ve worked with Kubernetes Engine . In general I’ve managed the clusters using kubectl and its commands like “kubectl get namespaces”, “kubectl get pods”, “kubectl create x” ...”,”kubectl apply x” etc, and to switch among clusters I’ve used kubectx in Ubuntu. To deploy a kubernetes dashboard I’ve used the steps from Github and I’ve accessed a url to monitoring the cluster. After that, I’ve worked with Pods Deployments, Removals, Deletions, Services, Jobs, ConfigMaps, Secrets and Stateful Sets.
### About Airflow in Kubernetes
In this Project I’ve deployed the Airflow in AWS Kubernetes using Apache Airflow Helm Chart Oficial. To work with Dag I’ve got an ETL example code from oficial Apache Airflow page. In the myvalues.yaml I’ve changed some configurations to work with GitSync, S3, Kubernetes Executor and LoadBalancer. After that I’ve deployed the Airflow in Kubernetes using Helm and I’ve opened in navigator to test the DAG and the ETL. At the last, I’ve used the helm to uninstall the Airflow from Kubernetes.
# Used Tools

*	Docker;
*	Ubuntu;
*	Rony Framework;
*	Github;
*	AWS ECR;
*	Python;
*	Kind;
*	Kubectl;
*	Kubectx(Only in Linux);
*	AWS EKS;
*	Eksctl;
*	EC2;
*	CloudFormation;
*	GCP Kubernetes Engine;
*	GCP Cloud Storage;
*	AWS S3;
*	Apache Airflow;

# Results
Working with Docker, Kubernetes and Airflow speeds up the deployment or modification of an application, enables better cluster management, and also makes it possible to organize tasks into small parts, and if a problem occurs, the solution will be faster. At the end, the company improves performance by reducing costs and speeding up delivery to the customer.

# Autor
Jaqueline Cella
*	Linkedin- @jaqueline-cella
*	Github- @jaquelinecella

