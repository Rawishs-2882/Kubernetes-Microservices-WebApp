<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:F8BBD0,50:CE93D8,100:B39DDB&height=180&section=header&text=Kubernetes%20Microservices&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Login%20%C2%B7%20Product%20%C2%B7%20Blog%20Services&descAlignY=58&descSize=15)

</div>

## Overview

A web application split into independent login, product and blog microservices, each containerized and orchestrated with Kubernetes, built to explore scalability and service discovery patterns in a real, working system rather than a toy example.

## Key Features

### Independent microservices
Login, product and blog functionality are each built and deployed as their own service, so they can scale and be updated independently.

### Containerized with Docker
Every microservice ships with its own Dockerfile, keeping builds reproducible and environment independent.

### Kubernetes orchestration
Deployments, services and networking are managed through Kubernetes manifests, including service discovery between the microservices.

### Scalable by design
Each service can be scaled independently based on load, rather than scaling the entire application as one unit.


## Tech Stack

<div align="center">
<img src="https://tech-orbit.wontory.dev/api?title=Microservices&tech=docker,kubernetes&size=420&duration=20" alt="tech stack orbit" width="420" />
</div>

Docker for containerization, Kubernetes for orchestration and service discovery, and REST APIs for communication between microservices.

## How It Works

Each microservice, login, product and blog, is built and containerized independently. Kubernetes manifests define deployments and services for each, with an ingress or internal service mesh handling routing and discovery between them.

## Setup and Run

1. Build each microservice image, for example `docker build -t login-service ./login-service`.
2. Repeat for the product and blog services.
3. Apply the Kubernetes manifests with `kubectl apply -f k8s/`.
4. Access the application through the configured ingress or service endpoints.

## Roadmap

- Add a shared API gateway in front of all services
- Add centralized logging across microservices
- Set up horizontal pod autoscaling based on load

## Status

> **Status:** This repository was scaffolded from the project description on the author's resume. Source code is being migrated and added here in stages. Reach out using the contact links below if you would like early access to the implementation.

## Let's Connect

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rawish0922@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rawishsarfraz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Rawishs-2882)
[![Phone](https://img.shields.io/badge/Call-+92--332--8747138-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](tel:+923328747138)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:B39DDB,50:CE93D8,100:F8BBD0&height=80&section=footer)

</div>
