# MICROSERVICES ARCHITECTURE AND DEPLOYMENT IN PUBLIC CLOUD PLATFORM
## _Dipanjan Biswas_



Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. These services are owned by small, self-contained teams.
Microservices architectures make applications easier to scale and faster to develop, enabling innovation and accelerating time-to-market for new features.

## Charecteristics

- Autonomous
- Specialized

## Benefits

- Agility
- Flexible Scaling
- Easy Deployment
- Technological Freedom
- Reusable Code

## Deploy a Django Application in AWS ECS Fargate (serverless)
1. We have to create Docker image of the Django Application
2. Docker Image can be pushed to Docker Hub or AWS ECR
3. Refer that Image in ECS task defination
4. Create ECS services in ECS cluster referring that task defination
5. AWS Application Load balancer added suring creation of services so that loads can be equally distributed.
6. (Optional) We can enable Autoscaling as well based on requirement
### Complete Architechture Diagram
![1](https://user-images.githubusercontent.com/89570404/222336167-e8553b0e-bd2d-4a21-8708-0be8287a7d4a.png)

### Microservice Deployment Cloud Architechture
![2](https://user-images.githubusercontent.com/89570404/222336213-e373cf56-5efd-4ea8-8125-3a2eb972bdfb.png)


### CICD Pipeline Deployment Automation
![3](https://user-images.githubusercontent.com/89570404/222336230-6425ef90-08d8-4c6d-a5da-8517fdd69347.png)

### Application is Running in AWS Fargate behind Application Load Balncer
![4](https://user-images.githubusercontent.com/89570404/222337122-ee8067e6-5390-446b-b1d3-621c2dd8be2f.png)


## Tech

Dillinger uses a number of open source projects to work properly:

- Python
- Django
- Postgresql
- Docker
- HTML
- GIT
- AWS

