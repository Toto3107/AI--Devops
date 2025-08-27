# Sentiment Analysis API with BentoML

A DevOps-friendly project showcasing **end-to-end deployment** of a Hugging Face sentiment analysis model.  
This project demonstrates packaging a model with **BentoML**, containerizing with **Docker**, deploying on **Kubernetes** via **Helm**, and managing cloud infrastructure with **Terraform**.  

It is designed to provide hands-on experience in **MLOps and DevOps workflows**, including CI/CD automation.

---

## Features

- **Hugging Face Transformers:** Sentiment analysis using DistilBERT (`sshleifer/tiny-distilbert-base-uncased-finetuned-sst-2`)  
- **BentoML Packaging:** Exposes the model as a REST API service  
- **Dockerized Deployment:** Containerize the API for portability  
- **Kubernetes + Helm:** Deploy scalable services on Kubernetes clusters  
- **Infrastructure as Code:** Manage cloud resources using Terraform  
- **CI/CD Ready:** Compatible with GitHub Actions or Jenkins pipelines  

---

## Prerequisites

- Python 3.10+  
- pip  
- Docker  
- Kubernetes cluster (minikube, kind, or cloud provider)  
- Terraform  

---

## Setup and Installation

### 1. Clone the repository
```bash
git clone https://github.com/Toto3107/sentiment-bento.git
cd sentiment-bento
# AI--Devops
Deployable Hugging Face Sentiment Analysis API using BentoML, Docker, Kubernetes, and Terraform for DevOps practice.
