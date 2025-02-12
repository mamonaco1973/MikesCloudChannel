# Terraform Setup Videos

## Quick Links

1. AWS Solution
   - [AWS + Terraform: Easy Setup](https://youtu.be/BCMQo0CB9wk)
   - [GitHub Project](https://github.com/mamonaco1973/aws-setup)
2. Azure Solution
   - [Azure + Terraform: Easy Setup](https://youtu.be/wwi3kVgYNOk)
   - [GitHub Project](https://github.com/mamonaco1973/azure-setup)
3. GCP Solution
   - [Google Cloud + Terraform: Easy Setup](https://youtu.be/3spJpYX4f7I)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-setup)
   
# Scaling in the Cloud: AWS Auto Scaling, Azure VMSS, and GCP MIGs

In this video series, we will explore deploying Flask-based microservices and implementing cloud-native scaling solutions across AWS, Azure, and Google Cloud Platform (GCP):

1. **Deploy Flask-based microservices** on virtual machines in AWS, Azure, and GCP.
2. **Use a document database** for microservice data storage:
   - **DynamoDB** for AWS
   - **CosmosDB** for Azure
   - **Firestore** for GCP
3. **Create machine images** of the deployed virtual machines using **Packer**.
4. **Implement cloud-native scaling solutions** with **Terraform**, tailored to each provider:
   - **Auto Scaling** for AWS
   - **Virtual Machine Scale Sets (VMSS)** for Azure
   - **Managed Instance Groups (MIGs)** for GCP
5. **Test scalability** by simulating load and triggering scaling events.
6. **Clean up resources** by destroying all infrastructure created during the process.

## Quick Links

1. [Introduction Video](https://youtu.be/i_T7Wu_mJ1k)
2. AWS Solution
   - [AWS Autoscaling Video](https://youtu.be/aBMM6vjC8d0)
   - [GitHub Project](https://github.com/mamonaco1973/aws-flask-asg)
3. Azure Solution
   - [Azure VMSS Video](https://youtu.be/a3l4qUfVvGQ)
   - [GitHub Project](https://github.com/mamonaco1973/azure-flask-vmss)
4. GCP Solution
   - [GCP Managed Instance Groups Video](https://youtu.be/AAOZOhREc5o)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-flask-mig)

# Serverless HTTP Endpoints - AWS Lambdas, Azure Functions and GCP Cloud Functions

This video series complements the [Scaling in the Cloud](https://github.com/mamonaco1973/cloud-scaling-intro/blob/main/README.md) series. In that series, we deployed a simple microservice using Python and the Flask framework.

In this series, we will deploy Python-based serverless functions in **AWS**, **Azure**, and **GCP**. These are referred to as *Flask-like* or *flasky* throughout the project documentation. The goal is to deploy an identical API from the Cloud Scaling series using the native serverless features of each cloud provider.

By the end of this series, you will learn how to deploy simple Python-based HTTP endpoints as serverless functions across all three major cloud platforms using Terraform.

We will walk through the following tasks:

1. **Deploy Python Code** for microservices using serverless technologies:
   - **Lambdas** for AWS
   - **Azure Functions** for Azure
   - **Cloud Functions** for GCP

2. **Use a document database** for microservice data storage:
   - **DynamoDB** for AWS
   - **CosmosDB** for Azure
   - **Firestore** for GCP

3. **Configure HTTP endpoints** to invoke the serverless code:
   - **API Gateway** for AWS
   - **Function App** for Azure
   - **Cloud Run** for GCP

4. **Secure the HTTP endpoints**:
   - **IAM Integration** for AWS
   - **Function Keys** for Azure
   - **JWT Token** for GCP

5. **Clean up resources** by destroying all infrastructure created during the process.

## Quick Links

1. [Introduction Video](https://youtu.be/NPhu0byKj_A)
2. AWS Solution
   - [AWS Lambda HTTP Endpoints](https://youtu.be/Psf56Fvn62E)
   - [GitHub Project](https://github.com/mamonaco1973/aws-flasky-lambdas)
3. Azure Solution
   - [Azure HTTP Function App](https://youtu.be/aIi8dtXs4qk)
   - [GitHub Project](https://github.com/mamonaco1973/azure-flasky-function-app)
4. GCP Solution
   - [GCP HTTP Cloud Functions](https://youtu.be/vVeci5df3Wc)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-flasky-cloud-functions)


# Containerizing Microservices Across AWS, Azure, and GCP

**This video series complements the [Scaling in the Cloud](https://github.com/mamonaco1973/cloud-scaling-intro/blob/main/README.md) series**, where we deployed a simple Python-based microservice using the Flask framework across different cloud platforms.

In this new series, we'll take that same microservice and containerize it using **Docker**. You'll learn how to:

- **Use a document database** for microservice data storage:
   - **DynamoDB** for AWS
   - **CosmosDB** for Azure
   - **Firestore** for GCP
- **Build a Docker container** for the microservice, optimizing it for cloud deployments.
- **Push the container image** to the appropriate container registry for each cloud provider:
  - **Amazon ECR (Elastic Container Registry)** for **AWS**  
  - **Azure Container Registry (ACR)** for **Azure**  
  - **Google Artifact Registry (GAR)** for **GCP**  
- **Deploy the container** using the simplest container runtime services offered by each cloud provider:
  - **AWS App Runner** for fully managed container deployments on AWS  
  - **Azure Container Apps** for serverless container hosting on Azure  
  - **Google Cloud Run** for scalable, stateless container execution on GCP  

## Quick Links

1. [Simple Cloud Containers: Docker Containers in AWS, Azure, and GCP](https://youtu.be/2BQB-OMAhH8)
2. AWS Solution
   - [Simple AWS Containers](https://youtu.be/hhtDigvwMwk)
   - [GitHub Project](https://github.com/mamonaco1973/aws-flask-container/)
3. Azure Solution
   - [Simple Azure Containers](https://youtu.be/eogMQjbBvTo)
   - [GitHub Project](https://github.com/mamonaco1973/azure-flask-container/)
4. GCP Solution
   - [Simple GCP Containers](https://youtu.be/9q0hXgSssPI)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-flask-container/)
