CI/CD Cloud Project (AWS + GitHub)
📌 Overview

This project demonstrates a complete CI/CD workflow using AWS services and GitHub. The goal of this project is to automate the deployment of a static website using secure cloud practices.

Here you can find all project-related media, workflow explanation, and deployment details.

❗ Problem Statement

Manual deployment of websites is:

Time-consuming
Error-prone
Not scalable
Insecure due to use of long-term AWS credentials

There was a need for a secure and automated deployment process using modern CI/CD practices.

🔧 Solution

To solve this problem, I built a CI/CD pipeline using AWS and GitHub:

Used Git & Git Bash for local version control
Managed source code on GitHub
Implemented AWS IAM OIDC for secure authentication (no hardcoded credentials)
Deployed a static website using Amazon S3

This setup enables secure and automated deployment instead of manual uploads.

🔄 Workflow
Code → Git & Git Bash → GitHub → AWS IAM OIDC → Amazon S3 → Live Website

🛠️ Services / Tools Used

Git & Git Bash – Version control and local repository management
GitHub – Source code hosting and CI/CD workflow integration
AWS IAM (OIDC) – Secure authentication using identity provider (no long-term access keys)
Amazon S3 – Static website hosting and deployment

📊 Key Features
Secure CI/CD pipeline setup
Identity-based AWS authentication (OIDC)
Automated deployment to S3
Real-world DevOps workflow implementation

🌐 Result
A fully functional static website deployed on AWS S3 with a secure and structured CI/CD pipeline.

🚀 Future Improvements
Add AWS CodePipeline or GitHub Actions for full automation
Integrate CloudFront for global content delivery
Add CloudWatch monitoring and logging
Create full architecture diagram for visualization

💡 Learning Outcome
This project helped me understand real-world CI/CD pipelines, secure AWS authentication, and cloud-based deployment workflows.
