# Car Dealership Project

> Car Dealership Reviews Web App  
> Capstone project for the IBM Full Stack Developer Professional Certificate

## 🚗 Project Overview

A full-stack web application that allows users to:  
- Browse and search **“Best Car”** dealerships by location  
- View existing customer reviews for each dealership  
- Submit their own reviews  
- See each review’s sentiment (😊 positive / 😞 negative) powered by IBM Watson NLU  

The frontend is built in **React**, the main web layer is a **Django** app, data services run as **Node.js** & **Flask** microservices, and data is stored in **MongoDB** (production) / **SQLite** (dev). The whole stack is containerized with **Docker** and deployable to Kubernetes on IBM Cloud.

## 🛠 Tech Stack

- **Frontend:** React, Axios, Bootstrap  
- **Web Layer:** Django, Django REST framework  
- **Data Services:**  
  - **Dealers & Reviews:** Node.js + Express + MongoDB  
  - **Sentiment:** Flask + IBM Watson NLU  
- **Databases:** SQLite (dev), MongoDB (prod)  
- **Containerization:** Docker, Docker Compose  
- **Cloud:** Kubernetes / OpenShift on IBM Cloud  
- **Languages:** JavaScript, Python, HTML, CSS, Dockerfile

## 📥 Prerequisites

- Node.js (v14+), npm  
- Python 3.8+ & `venv`  
- MongoDB (or Docker)  
- IBM Cloud account with Watson NLU credentials  
- Docker & Docker Compose (for microservices)  

## License

This repository is a fork of [xrwvm-fullstack_developer_capstone](https://github.com/ibm-developer-skills-network/xrwvm-fullstack_developer_capstone) by IBM Developer Skills Network.  
It is released under the Apache Version 2.0 License:

> Copyright (c) 2024 IBM Developer Skills Network  
> Copyright (c) 2025 Wei (Kion) Zhang

See [LICENSE](./LICENSE) for details.
