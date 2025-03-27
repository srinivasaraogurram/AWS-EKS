AWS EKS - Create Kubernetes cluster on Amazon EKS | the easy way
- EKS
    - What is EKS
    - How to use EKS
    - Demo: Creating a Kubernetes Cluster with EKS

![alt text](image.png)

What is EKS?

 - Managed Kubernetes Service
   - AWS Manages Master Nodes
   - Installs Necessary apps pre-installed
     - Container Runtime
     - Master Process
  - Scaling and Backups
![alt text](image-1.png)

![alt text](image-2.png)

User will only create worker Nodes
![alt text](image-3.png)

How to use EKS?
- Step 1 | Setup or Preparation Steps
 - Create AWS Account
 - Create a VPC
 - Create an IAM Role wit Security Groups
 - ![alt text](image-4.png)

 - ![alt text](image-5.png)

- Step 2: Create Cluster Control Plane
  - choose cluster name, k8s version
  - choose region and VPC for your cluster
  - set security for your cluster
![alt text](image-6.png)

-Step 3: Create as a Node Group ( group of Nodes
Choose Cluster it will attach to 
Define Security Group select instance type and resource)

![alt text](image-7.png)


![alt text](image-8.png)

![
   
](image-9.png)
 kubectl

 ![alt text](image-10.png)

 ![alt text](image-11.png)
 ![alt text](image-12.png)

 ![alt text](image-13.png)

 ![alt text](image-14.png)

 ![alt text](image-15.png)

 ![alt text](image-16.png)
 ![alt text](image-17.png)
 ![alt text](image-18.png)
 ![alt text](image-19.png)
 ![alt text](image-20.png)
 ![alt text](image-21.png)
 ![alt text](image-22.png)
 ![alt text](image-23.png)
 ![alt text](image-24.png)
 ![alt text](image-25.png)
 ![alt text](image-26.png)
 ![alt text](image-27.png)
 ![alt text](image-28.png)
 ![alt text](image-29.png)
 ![alt text](image-30.png)
 ![alt text](image-31.png)
 ![alt text](image-32.png)
 ![alt text](image-33.png)
 ![alt text](image-34.png)