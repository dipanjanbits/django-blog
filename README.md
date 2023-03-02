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
[![N|Solid](https://django-blog-dip.s3.amazonaws.com/1.png)]

### Microservice Deployment Cloud Architechture
[![N|Solid](https://django-blog-dip.s3.amazonaws.com/2.png)]

### CICD Pipeline Deployment Automation
[![N|Solid](https://django-blog-dip.s3.amazonaws.com/3.png)]


## Tech

Dillinger uses a number of open source projects to work properly:

- Python
- Django
- Postgresql
- Docker
- HTML
- GIT
- AWS

