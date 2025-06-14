# DeepMind Portfolio

This repository contains five projects that showcase progressive levels of complexity and development effort. The first three combine LLMs with neuroscience, demonstrating different approaches to integrating AI with neuroscience principles. The fourth project applies LLM capabilities to a practical business application - a nail beauty shop appointment scheduler. The fifth project demonstrates a full-stack, AI-powered platform for orchard farm management, integrating IoT, ML, and advanced web technologies. All projects leverage AWS cloud services and advanced ML technologies to demonstrate real-world applications of AI.

## Projects Overview

### [Project 1: NeuroText Analyzer](./project1-neurotext-analyzer)

A specialized tool that uses LLMs to analyze neuroscience research papers and datasets, extracting key insights, findings, and relationships from neuroscience literature.

**Development Time:** 10 Hours
**Complexity Level:** Entry-level

**Key Technologies:**
- **AWS Lambda** for serverless text extraction and processing
- **AWS DynamoDB** for storing neuroscience entities and relationships
- **AWS Step Functions** for orchestrating the analysis pipeline
- **AWS SageMaker** for hosting custom NLP models
- **XGBoost** for paper classification and insights extraction
- **OpenAI API/Llama** for text understanding and analysis
- **Docker** and **LocalStack** for local development

[View Project Details](./project1-neurotext-analyzer)

### [Project 2: BrainInspired LLM Enhancement](./project2-braininspired-llm-enhancement)

A system that implements neuroscience-inspired attention mechanisms and memory systems to enhance LLM performance on specific tasks, based on principles from hippocampal memory systems.

**Development Time:** 20 Hours
**Complexity Level:** Intermediate

**Key Technologies:**
- **AWS SageMaker** for training and hosting LLMs with custom architectures
- **AWS Lambda** for serverless memory indexing and context management
- **AWS DynamoDB** for episodic memory storage
- **AWS Step Functions** for orchestrating brain-inspired processing
- **XGBoost/Random Forest** models for supporting classification tasks
- **MLflow** for tracking experiments with different brain-inspired architectures
- **Modified transformer attention mechanisms** inspired by neural processing
- **Docker** and **LocalStack** for local development

[View Project Details](./project2-braininspired-llm-enhancement)

### [Project 3: NeuroLLM Assistant Platform](./project3-neurollm-assistant-platform)

A comprehensive platform that combines LLMs with neuroscience data analysis to provide personalized cognitive insights and recommendations based on neural data patterns.

**Development Time:** 30 Hours
**Complexity Level:** Advanced

**Key Technologies:**
- **AWS SageMaker** for training and hosting LLMs and ML models
- **AWS Lambda** for serverless data processing and analysis
- **AWS DynamoDB** for user profiles and session data
- **AWS Neptune** for neuroscience knowledge graph
- **AWS S3** for neuroscience data lake
- **AWS ECS** for container orchestration
- **AWS Step Functions** for complex workflow orchestration
- **XGBoost/Random Forest** for anomaly detection and pattern classification
- **MLflow** for experiment tracking and model registry
- **React** and **CloudFront** for interactive dashboard
- **Docker** and **LocalStack** for local development

[View Project Details](./project3-neurollm-assistant-platform)

### [Project 4: Beauty Nail Shop Appointment Scheduler](./project4-beauty-nail-scheduler)

A comprehensive web application for scheduling appointments at a nail beauty shop, enhanced with LLM-powered features for intelligent customer interaction and business optimization.

**Development Time:** 30 Hours
**Complexity Level:** Advanced

**Key Technologies:**
- **React** for modern, responsive frontend UI
- **Go (Golang)** for high-performance backend API
- **AWS DynamoDB** for scalable database storage
- **AWS Lambda** for serverless AI processing
- **AWS Cognito** for authentication and user management
- **OpenAI API/Self-hosted LLM** for intelligent features
- **LangChain/LlamaIndex** for LLM application framework
- **Gin/Echo** Go web framework for RESTful APIs
- **Docker** for containerization and deployment
- **AWS CDK** for infrastructure as code

[View Project Details](./project4-beauty-nail-scheduler)

### [Project 5: OrchardHub – Smart Orchard Management Platform](./project5-orchardhub)

A full-stack, AI-powered platform for orchard farm management, integrating modern web technologies, IoT sensor data, machine learning, and advanced analytics. OrchardHub serves both customers and farm operators, providing a responsive website, inventory and harvest management, crop forecasting, customer ordering, and a comprehensive analytics dashboard.

**Development Time:** 34 Hours
**Complexity Level:** Advanced

**Key Technologies:**
- **React** for frontend UI and dashboards
- **Go (Golang)** for high-performance backend API
- **AWS DynamoDB** for scalable data storage
- **AWS Lambda** for serverless ML and IoT processing
- **AWS SageMaker** for crop prediction and analytics
- **AWS Cognito** for authentication
- **OpenAI API/LangChain/LlamaIndex** for LLM-powered features
- **XGBoost** for yield prediction and anomaly detection
- **IoT Core** for sensor integration
- **D3.js/Recharts** for data visualization
- **Docker** and **LocalStack** for local development
- **AWS CDK** for infrastructure as code

[View Project Details](./project5-orchardhub)

## Project Progression

The five projects represent a natural progression in complexity, development effort, and practical application of AI technologies:

1. **Project 1 (10 hours)** uses serverless Lambda functions and DynamoDB to create a scalable system for analyzing neuroscience texts with LLMs, representing an entry point into combining these technologies.

2. **Project 2 (20 hours)** goes deeper by deploying modified LLM architectures on SageMaker with neuroscience-inspired memory systems in DynamoDB, implementing brain-inspired memory and attention mechanisms within a cloud-native architecture.

3. **Project 3 (30 hours)** represents an advanced integration within the neuroscience domain, with a comprehensive AWS architecture using SageMaker, Neptune, ECS, and Step Functions to create a complete platform that processes neural data through LLMs and ML models to provide actionable insights.

4. **Project 4 (30 hours)** applies the LLM integration skills to a practical business domain, creating a complete appointment scheduling application for a nail beauty shop. This project demonstrates how LLMs can enhance traditional web applications by adding intelligent conversation capabilities, personalized recommendations, and natural language processing of complex user requests, all built with a high-performance Go backend and React frontend.

5. **Project 5 (34 hours)** is the most advanced, combining all previous skills to build a full-stack, AI-powered orchard management platform. It integrates IoT sensor data, machine learning for crop forecasting, LLM-powered customer support, and advanced analytics, providing a real-world example of how modern AI and cloud technologies can transform traditional industries.

## Common Technology Stack Across Projects

### AWS Services
- **SageMaker**: For hosting and training LLMs and ML models
- **Lambda**: For serverless processing functions
- **DynamoDB**: For flexible, scalable data storage
- **Step Functions**: For orchestrating complex workflows
- **CloudWatch**: For monitoring and observability
- **SQS**: For message queuing and asynchronous processing
- **Redshift**: For data warehousing and analytics
- **ECS**: For container orchestration and scaling

### ML & Data Science
- **XGBoost/Random Forest**: For classification and anomaly detection
- **MLflow**: For experiment tracking and model registry
- **LLM Integration**: Using various LLM models across all projects

### Data Pipeline & Orchestration
- **Apache Airflow**: For complex workflow orchestration and ETL processes
- **ETL Pipelines**: For data transformation and loading into warehouses

### Development & Deployment
- **Docker & Docker Compose**: For containerization and consistent environments, including multi-service orchestration for local development and deployment
- **LocalStack**: For local AWS service emulation
- **GitHub Actions**: For CI/CD pipelines
- **Infrastructure as Code**: Using AWS CDK or Terraform

## Learning Extensions

All projects have been enhanced with additional AWS services and data engineering technologies for learning purposes. Each project README includes an "Enhanced Architecture" section with a detailed Mermaid diagram and Docker implementation notes, demonstrating how to build scalable, production-grade cloud solutions.

## Getting Started

Each project contains its own detailed README with setup instructions, architecture diagrams, and usage examples. The READMEs include a breakdown of development time by phase to help you understand the effort involved in each component.

Navigate to the individual project directories to learn more about each implementation.

## Local Development Environment

All projects can be run locally using Docker and LocalStack to emulate AWS services:

1. Install prerequisites:
```bash
# Install Docker
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh

# Install LocalStack
pip install localstack
```

2. Clone the repository:
```bash
git clone <repository-url>
cd deepmind-portfolio
```

3. Follow the specific setup instructions in each project's README.

## License

This repository is licensed under the MIT License - see the LICENSE file for details.
