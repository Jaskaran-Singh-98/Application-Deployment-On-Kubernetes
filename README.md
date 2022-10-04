# Multi Tier Application Deployment on Azure Kubernetes Service
<img width="926" alt="image" src="https://user-images.githubusercontent.com/93183118/192150359-26d5f987-20d8-42c7-ab4a-69937b9377ef.png">

[backend](https://github.com/Jaskaran-Singh-98/ApplicationDeployment/tree/main/fullstackapp/backend) -> This Folder contains the files related to Python backend code and the Dockerfile used to build the docker image of the backend application.

[frontend](https://github.com/Jaskaran-Singh-98/ApplicationDeployment/tree/main/fullstackapp/frontend) -> This Folder contains the files related to  react frontend code and the Dockerfile used to build the docker image of the frontend application.

[kubernetes](https://github.com/Jaskaran-Singh-98/ApplicationDeployment/tree/main/fullstackapp/kubernetes) -> This Folder contains the files related to yaml files required to deploy 3 tier application on kubernetes.

[Application Deployment using Azure Pipelines](https://github.com/Jaskaran-Singh-98/ApplicationDeployment/blob/main/azure-pipelines.yml) -> This is a azure devops pipeline yaml file which has been used to deploy the application on azure kubernetes service.In this pipeline  Docker images are getting build from Dockerfile, which are then pushed to Azure Container Registry and from that registry latest images are getting pulled for kubernetes yaml files so that applocation can be deployed on azure kubernetes service.
