![Build Status](https://github.com/TU-USUARIO/serverless-data-pipeline/actions/workflows/python-ci.yml/badge.svg)

# Serverless Data Pipeline
A serverless event-driven data pipeline using **AWS Lambda, Kinesis, and DynamoDB**.  
It processes real-time events and stores them in DynamoDB.

## ✅ Tech Stack
- Python 3.9
- AWS Lambda, Kinesis, DynamoDB
- AWS SAM for deployment

## ✅ Features
✔ Real-time event ingestion  
✔ Serverless architecture  
✔ Scalable and cost-efficient  

## ✅ Setup
```bash
pip install -r requirements.txt
sam build
sam deploy --guided

## ✅ Run Tests
PYTHONPATH=. pytest --cov=src

## ✅ CI/CD
This project uses GitHub Actions for:
- Linting
- Unit testing
- Coverage report
Workflow: .github/workflows/python-ci.yml

