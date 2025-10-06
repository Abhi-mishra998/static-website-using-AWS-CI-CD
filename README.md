

---

# Static Website Deployment with AWS CodePipeline

## Project Overview

This project demonstrates the automation of static website deployment using AWS services, including CodePipeline, CodeBuild, and S3. By integrating these tools, the pipeline automatically deploys website updates upon code changes, ensuring efficient and reliable delivery.

https://drive.google.com/drive/folders/1jseEtcu1nqN67IvSx5OjRu1qOf6jDR9h
(codepipeline)

---

## 🛠️ Technologies Used

* **AWS CodePipeline**: Automates the CI/CD workflow.
* **AWS CodeBuild**: Builds and packages the website content.
* **Amazon S3**: Hosts the static website.
* **GitHub**: Source code repository.
* **AWS IAM**: Manages permissions and access control.

---

## 🚀 Project Workflow

1. **Source Stage**: Detects changes in the GitHub repository.
2. **Build Stage**: Uses CodeBuild to package the website files.
3. **Deploy Stage**: Deploys the packaged files to an S3 bucket configured for static website hosting.

---

## 🧪 Setup Instructions

### 1. Create a GitHub Repository

* Initialize a new repository and add your static website files (e.g., `index.html`, `styles.css`, `script.js`).

### 2. Configure Amazon S3 Bucket

* Create a new S3 bucket.
* Enable static website hosting in the bucket properties.
* Set the index document (e.g., `index.html`).

### 3. Set Up AWS CodePipeline

* Navigate to the AWS CodePipeline console.
* Create a new pipeline:

  * **Source Provider**: GitHub
  * **Build Provider**: AWS CodeBuild (optional, depending on your setup)
  * **Deploy Provider**: Amazon S3
* Define the stages and actions as per the project workflow.

---

## ✅ Key Features

* **Automated Deployments**: Code changes trigger automatic deployments to S3.
* **Version Control Integration**: Seamless integration with GitHub for source control.
* **Scalability**: Leverages AWS's scalable infrastructure for hosting.

---

## Author: Abhishek Mishra





















