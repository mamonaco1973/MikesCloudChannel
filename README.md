# Terraform Setup Videos

In this video series, you'll learn how to set up minimal cloud infrastructure across **AWS**, **Azure**, and **Google Cloud** using **Terraform**. Designed for beginners, each step-by-step tutorial guides you through provisioning essential cloud resources, automating configurations, and managing infrastructure efficiently with Terraform.

- **Terraform Basics:** Installing and configuring Terraform alongside cloud-specific CLI tools:
  - **AWS CLI**
  - **Azure CLI**
  - **gcloud CLI**
  - **Packer** for image automation
- **Cloud Setup:** Creating secure credentials for each platform:
  - **AWS:** IAM Users and Access Keys
  - **Azure:** App Registrations and Client Credentials
  - **Google Cloud:** Service Accounts and API Activation
- **Infrastructure Provisioning:** Deploying minimal environments, including:
  - **🌩️ AWS:** A VPC with a public subnet and an EC2 instance running Ubuntu with Apache installed automatically.
  - **🔷 Azure:** A Virtual Network (VNet), a public subnet, and an Ubuntu VM with Apache pre-installed during setup.
  - **☁️ Google Cloud:** An Ubuntu VM that installs Apache on startup using an automated script.
- **Verification:** Accessing and validating your cloud resources after deployment.
- **Security & Environment Management:** Using environment variables for secure credential management.
- **Resource Cleanup:** Safely tearing down infrastructure to avoid unnecessary costs.

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

# Configuring GitHub Actions in AWS, Azure and GCP

This video series extends the previous tutorial where a Python-based microservice using Flask was deployed across AWS, Azure, and GCP using containers. The focus now is on configuring **GitHub Actions** to automate the build, test, and deployment processes entirely within the GitHub ecosystem.

GitHub Actions is a robust CI/CD tool that helps streamline development pipelines, reduce manual errors, and ensure consistent deployments across environments.

## Quick Links

1. [GitHub Actions](https://youtu.be/Ngsz9pfgBUo)
2. AWS Solution
   - [AWS GitHub Actions](https://youtu.be/FQPjUdQ4hLM)
   - [GitHub Project](https://github.com/mamonaco1973/aws-flask-container/)
3. Azure Solution
   - [Azure GitHub Actions](https://youtu.be/MGzcVCAfouQ)
   - [GitHub Project](https://github.com/mamonaco1973/azure-flask-container/)
4. GCP Solution
   - [GCP GitHub Actions](https://youtu.be/ZMlJ_Cj7tY0)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-flask-container/)
    
# Deploying Active Directory in the Cloud

In this series, we’ll deploy Active Directory across the three major cloud platforms: AWS, Azure, and Google Cloud. You’ll gain hands-on experience with:

- **Setting up cloud-managed Active Directory**:
  - AWS Directory Service in AWS
  - Entra Domain Services (aka ADDS) in Azure
  - Google Managed Microsoft AD in Google Cloud
- **Configuring secure networking**: VPCs, VNets, and subnets to support domain connectivity.
- **Joining servers to the AD domain**: Both Linux and Windows servers.
- **Configuring SSSD**: System Security Services Daemon to authenticate Active Directory users on Linux.
- **Managing domain-joined servers**:
  - Creating Organizational Units (OUs)
  - Managing users and groups
- **Storing administrator credentials securely**:
  - AWS Secrets Manager in AWS
  - Azure Key Vault in Azure
  - Google Secret Manager in Google Cloud
- **Comparing pricing, capabilities, and limitations**: Across cloud providers.
- **Automation**: Using Terraform and shell scripts to fully automate the deployment process across all three clouds—from provisioning the directory service to joining servers to the domain.

## Quick Links

1. [Deploying Active Directory in the Cloud](https://youtu.be/H5lKJPJBL5s)
2. AWS Solution
   - [AWS Directory Service](https://youtu.be/1lnSxfFmGPY)
   - [GitHub Project](https://github.com/mamonaco1973/aws-active-directory/)
3. Azure Solution
   - [Azure Entra Domain Services](https://youtu.be/XqRJsGLBOfc)
   - [GitHub Project](https://github.com/mamonaco1973/azure-directory/)
4. GCP Solution
   - [GCP Managed Active Directory](https://youtu.be/gwn_KkiQ99s)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-directory/)

# Containerizing Applications Using Kubernetes in The Cloud

**This video series complements the [Scaling in the Cloud](https://github.com/mamonaco1973/cloud-scaling-intro/blob/main/README.md) and the [Simple Cloud Containers](https://github.com/mamonaco1973/container-intro/blob/main/README.md) series**, where we deployed a simple Python-based microservice using the Flask framework across different cloud platforms.

In this new series, we'll take that same microservice and containerize it using **Docker**, then deploy it to **Kubernetes clusters** running on the managed Kubernetes services provided by each cloud platform.

This is a **fully automated deployment** of containerized microservices and web apps across AWS, Azure, and GCP — powered by infrastructure-as-code and cloud-native tooling.

We'll build and deploy:

- **A document database-backed microservice** using:
  - **DynamoDB** for AWS  
  - **CosmosDB** for Azure  
  - **Firestore** for GCP  

- **A Docker container** for the Flask microservice, optimized for Kubernetes deployments.

- **Additional standalone Docker containers** that run classic JavaScript games like **Tetris**, **Frogger**, and **Breakout**.

- **Cloud-native container registry workflows**, pushing images to:
  - **Amazon ECR (Elastic Container Registry)**  
  - **Azure Container Registry (ACR)**  
  - **Google Artifact Registry (GAR)**  

- **Kubernetes workloads on managed clusters**, deploying everything to:
  - **Amazon EKS**  
  - **Azure AKS**  
  - **Google GKE**  

- **Kubernetes manifests** including **Deployments**, **Services**, and **Ingress** resources for scalable, fault-tolerant workloads.

- **NGINX as a unified Ingress controller**, exposing all services and games behind a single Load Balancer per cloud.

## Quick Links

1. [Kubernetes In The Cloud](https://youtu.be/6A-DO_ymDQI)
2. AWS Solution
   - [Elastic Kubernetes Service](https://youtu.be/Tl2y86V5XSQ)
   - [GitHub Project](https://github.com/mamonaco1973/aws-k8s/)
3. Azure Solution
   - [Azure Kubernetes Service](https://youtu.be/LhFiK1otC7o)
   - [GitHub Project](https://github.com/mamonaco1973/azure-k8s/)
4. GCP Solution
   - [Google Kubernetes Engine](https://youtu.be/ALOM53zq-lw)
   - [GitHub Project](https://github.com/mamonaco1973/gcp-k8s/)
