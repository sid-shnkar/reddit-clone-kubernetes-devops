# reddit-clone-kubernetes-devops
Reddit app clone deployment on Kubernetes with ingress, using AWS, Docker, and Kubernetes

Configuration details: 
1. **CI server EC2 instance name:** reddit-kubernetes-ci-server (t2.micro)
2. **Deployment server EC2 instance name:**  reddit-kubernetes-deployment (t2.medium)
3. **Docker reddit app docker hub image name :** reddit-clone
4. **Kubernetes reddit app deployment name :** reddit-clone-deployment
5. **Kubernetes reddit app service name :** reddit-clone-service
6. **Kubernetes reddit app ingress name :** ingress-reddit-app
7. **App URL format -** http://EC2_INSTANCE_PUBLIC_IP_ADDRESS:3000


<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Description](#description)
  * [Technologies](#technologies-used)
  * [Screenshots](#screenshots)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Commands used](#commands-used)


<!-- ABOUT THE PROJECT -->
## About The Project

### Description
NodeJs To-do List app completely automated deployment using Jenkins, AWS EC2, Docker and GitHub CI/CD

### Technologies used
1. AWS EC2
2. Kubernetes (with Ingress)
3. Docker
4. GitHub


### Screenshots

![screenshot-1](pics/p1.png)
![screenshot-2](pics/p2.png)
![screenshot-3](pics/p3.png)
![screenshot-4](pics/p4.png)
![screenshot-5](pics/p5.png)
![screenshot-6](pics/p6_service.png)
![screenshot-7](pics/p7_expose_port.png)
![screenshot-8](pics/final_redit.png)
![screenshot-9](pics/p8_ingress_start.png)
![screenshot-10](pics/p9_ingress_working.png)

<!-- GETTING STARTED -->
## Getting Started

To get started with the project, follow these steps:

### Prerequisites

* AWS account
* GitHub account

### Commands used

**Note:** 
* Make sure to enable port 3000 inbound traffic while creating the EC2 instance or edit the security group if you already have created it.


