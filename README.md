# Automated Web Application Deployment with Terraform and Jenkins
<p align="center">

![Screenshot 2024-10-26 215602](https://github.com/user-attachments/assets/925daa40-1ffa-464b-9f27-f8c27ce93e8b)

</p>

Lab Summary: Deploying a Jenkins CI/CD Pipeline on AWS EC2
In this lab, I successfully deployed Jenkins on an Amazon EC2 instance and set up a CI/CD pipeline to automate builds and deployments. 



<h2>Environments and Technologies Used</h2>

- Amazon S3
- Terraform
- Jenkins
- PowerShell
- AWS CLI

<h2>Operating Systems Used </h2>

- Amazon Linux

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1 - Setting Up the Infrastructure with Terraform
- Step 2 - Set Up Jenkins for CI/CD
- Step 3 - Create a Jenkins Pipeline for CI/CD
- Step 4 - Test the Deployment

<h2>Deployment and Configuration Steps</h2>

- Step 1 - Setting up the Infrastructure with terraform
- 1. Define your Terraform configuration
- 2. Create a new directory for your project and set up Terraform files:
![Screenshot 2024-10-26 112937](https://github.com/user-attachments/assets/8ca00fa4-596a-4a41-a4a0-ece720c952b3)

- 3. Create a .tf File for Terraform Configuration
- 4. In your aws-terraform-jenkins directory, create a new file named main.tf
  ![Screenshot 2024-10-26 131613](https://github.com/user-attachments/assets/93267e79-e65f-4bf3-a666-973b96020a11)


- 5. Write the Terraform Code:
  ![Screenshot 2024-10-26 115303](https://github.com/user-attachments/assets/ca8d0467-6979-49f2-b8c4-0f2b722ec7bb)

- 6. Initialize Terraform:
  ![Screenshot 2024-10-26 115542](https://github.com/user-attachments/assets/c7565c16-6b90-42e4-ae74-e3bc352f0829)
- Now the EC2 Instance is created.
  ![Screenshot 2024-10-26 140400](https://github.com/user-attachments/assets/e300e39d-b60c-40f5-a80f-750b77157044)

- Step 2 - Set Up Jenkins for CI/CD on the EC2 Instance

- 1. SSH into the instance:
  ![Screenshot 2024-10-26 145737](https://github.com/user-attachments/assets/1e109b79-239c-4ca7-97b9-b4164e8b9042)

- 2. Install Java (Jenkins requires Java)
  ![Screenshot 2024-10-26 150211](https://github.com/user-attachments/assets/ba0ab691-eaaa-4bfb-9e98-16ebca6088b8)

- 3. Add Jenkins Repository
  ![Screenshot 2024-10-26 150538](https://github.com/user-attachments/assets/832707f7-a964-40a4-9086-7fac065bb222)

- 4. Install Jenkins
  ![Screenshot 2024-10-26 151150](https://github.com/user-attachments/assets/940523b6-6d9c-4b1a-9dce-5fe61477469c)

- 5. Retrieve Initial Admin Password
  ![Screenshot 2024-10-26 151945](https://github.com/user-attachments/assets/61d94f6f-e7ed-44f5-9738-421150bdce5d)

- 6. Access Jenkins on Browser
  ![Screenshot 2024-10-26 152435](https://github.com/user-attachments/assets/a8cba7ea-f1d7-4dca-b8f3-f020d8bb6fd7)
  ![Screenshot 2024-10-26 152631](https://github.com/user-attachments/assets/0dd78015-7f2b-41ad-a439-49c57509def6)
  ![Screenshot 2024-10-26 152829](https://github.com/user-attachments/assets/7e2650b8-0ef5-43b1-82e4-8072290923a5)

- Step 3 - Create a Jenkins Pipeline for CI/CD
- 1. Install Necessary Plugins
  ![Screenshot 2024-10-26 155644](https://github.com/user-attachments/assets/cc6efb52-7e70-4ebe-881f-55c0aa108700)

- 2. Create a New Pipeline Job
  ![Screenshot 2024-10-26 160157](https://github.com/user-attachments/assets/7049537b-c589-4e65-bade-fbe4c6069d75)

- 3. Write a Jenkins Pipeline Script
  ![Screenshot 2024-10-26 160830](https://github.com/user-attachments/assets/956f5d6d-e8aa-4806-a946-4209fe45dbf4)
  ![Screenshot 2024-10-26 161041](https://github.com/user-attachments/assets/e5463068-bdcb-4645-ad20-40df4d3cf33e)
  ![Screenshot 2024-10-26 161358](https://github.com/user-attachments/assets/88b51d3e-ba41-48dd-933e-e4ac840264c1)
  ![Screenshot 2024-10-26 161537](https://github.com/user-attachments/assets/c77fdb1a-59d3-4a9b-855a-a6a7670e0716)

- Step 4 - Test the deployment
  ![Screenshot 2024-10-26 215104](https://github.com/user-attachments/assets/a9feb074-82a0-47c6-812f-f00f390ea547)












  













