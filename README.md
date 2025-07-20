Today, we will set up GitHub Actions CI/CD with the help of AWS and Terraform. The CI/CD platform will be GitHub, the infrastructure will be created on AWS, and Terraform will be used to manage the infrastructure.
Problem : Create a simple website with automated deployment using AWS services.

Solution : We built a complete CI/CD pipeline where:

Developer writes code and pushes to GitHub
GitHub automatically builds and deploys the website
Website runs on AWS cloud infrastructure
Key Components :

Source Code: Simple “Hello World” website
Container: Website packaged in Docker
Cloud Storage: AWS ECR holds our Docker image
Cloud Hosting: AWS ECS runs our website
Automation: GitHub Actions handles deployment
End Result :

Push code → Website automatically goes live
No manual deployment steps needed
Everything runs in AWS cloud
It’s like having a robot that takes your code, packages it, and puts it live on the internet automatically whenever you update it.

2. The folder structure of our code is shown below.


3. Before we proceed, create a GitHub repository — whether public or private, depending on your preference. Then, clone the empty repository to your local machine to start writing the code.

4. Now, let’s proceed with writing the code.
