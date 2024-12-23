# DevOps-Project-3-Tier-YelpCamp-Application-Deployment-monitoring-and-log-aggregation-newrelic-Aws
![image](https://github.com/user-attachments/assets/2a01ff97-e079-4ac9-b427-db13fc73fc56)

High-level architecture diagram of the project is as shown in the screenshot attached above. 

This DevOps Project aims to create the infrastructure of EKS Cluster, Elastic Container Registry (ECR), Jenkins Master, Jenkins Slave and SonarQube Server with the help of Terraform. Creation of CI/CD pipeline using Jenkins for the purpose of Deployment of the Application. For Monitoring and Log Aggregation NewRelic had been used which is shown in the high-level architecture diagram above. Alerts had been created in NewRelic and will send the Email on the Group Email Id if the Alert condition crosses the threshold. In this project Mapbox, Cloudinary and MongoDB had been used. The credentials for Mapbox, Cloudinary and MongoDB had been encrypted using base64 and provided through the kubernetes secrets using helm chart present in the GitHub Repository https://github.com/singhritesh85/helm-chart-yelp-camp.git.

```
Source Code:- https://github.com/singhritesh85/YelpCamp.git

Helm Chart:-  https://github.com/singhritesh85/helm-chart-yelp-camp.git

Reference:-   https://github.com/Colt/YelpCamp.git
```
