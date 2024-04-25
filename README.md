# Final Project of AWS course
Cloud computing is a broad field of computing that deserves a lot of attention from students in the area. Therefore, learning to manage a cloud service provider such as AWS, through a project, is a plus to your knowledge, in addition to allowing you to reach new frontiers.

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:1400/1*2-b5UkCIf7iF0eCTc-DFeQ.gif" alt="" width="600" height="350"/>  
</p>

# Index
1. [About the project](#about-the-project)
2. [Technologies used](#technologies-used)
3. [Installation and use](#installation-and-use)
4. [Author](#author)
5. [Licence](#licence)

# About the project <a name='about-the-project'></a>

The objective of the project is to use the services of the AWS provider to create a virtual infrastructure that allows us to deploy an application. To speed up the process it is a good idea to use technologies that can create and destroy resources with code, for this we can use Terraform.

# Technologies used <a name='technologies-used'></a>

The project use...
- **Terraform:** to create the resources in AWS with code. 

# Installation and use <a name='installation-and-use'></a>

**IMPORTANT: To use the code, it is a good idea to do it with the Linux operating system. The recommended distribution is Ubuntu.**

Before you begin, on your PC you need to configure your AWS credentials using the AWS CLI. Additionally, you must install terraform to use files with a .tf extension. If you have any problems with this, you can read the documentation at the following URLs:

- https://docs.aws.amazon.com/es_es/cli/latest/userguide/getting-started-install.html
- https://developer.hashicorp.com/terraform/install

## Step #1: VPC creation in AWS with Terraform
With the terminal change the directory to the project folder, and use the commands: 
```sh
terraform init
```
```sh
terraform validate
```
```sh
terraform plan
```
```sh
terraform apply
```
In summary, these commands are used to prepare the working directory, validate the code, view changes, and create the infrastructure in AWS.

It is important to mention that by doing this you will be consuming credits in AWS, so if you want to eliminate the infrastructure you can use:

```sh
terraform destroy
```


# Author <a name='author'></a>
This project has been created by Bryan Rosillo. You can contact me by the following means: 
- [Linkedin](https://www.linkedin.com/in/bryan-stiven-rosillo-guayanay-a249b9294/)
- [Facebook](https://www.facebook.com/profile.php?id=100012860282061)
- [WhatsApp](https://wa.me/0997761333)
 
# Licence <a name='licence'></a>
The project presented has an MIT license.
