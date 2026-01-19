<<<<<<< HEAD
### Network Security Projects For Phising Data

Setup github secrets:
AWS_ACCESS_KEY_ID=

AWS_SECRET_ACCESS_KEY=

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 788614365622.dkr.ecr.us-east-1.amazonaws.com/networkssecurity
ECR_REPOSITORY_NAME = networkssecurity


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
=======
# Network Security Enhancement using MLOps

An ML-driven network security system designed to detect malicious traffic
using machine learning models and MLOps best practices.

## Problem Statement
Traditional rule-based intrusion detection systems struggle to detect
evolving cyber threats. This project applies machine learning and MLOps
principles to build a scalable and maintainable intrusion detection system.

## System Overview
- Data preprocessing and feature engineering
- Machine learning model training and evaluation
- Model versioning and pipeline automation
- REST-based inference for real-time prediction
- Containerized deployment

## Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- MLflow (model tracking)
- Docker
- Flask / FastAPI

## Architecture
The system follows an MLOps-driven architecture:
- Training pipeline for model building and evaluation
- Model registry for version control
- Inference service for real-time predictions
- Containerized deployment for reproducibility

## Results
- Achieved high accuracy in detecting malicious network traffic
- Reduced false positives compared to traditional approaches
- Enabled reproducible and scalable ML workflows

## Project Type
Final Year Academic Project (Group Project)

## My Contribution
- Designed ML pipeline for intrusion detection
- Implemented data preprocessing and model training
- Integrated model versioning and inference workflow
- Contributed to system architecture and evaluation

## Documentation
Detailed project report and architecture diagrams are available in the `docs/` folder.
>>>>>>> 68d20234c3ecca15870d987692c478afb7d38356
