<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is about a web application development with docker and aws services
* Version 1 - Static files on web server
* Version 2 - Verification of static form file with php 
* Version 3 - Integration with DynamoDB service on aws using php + sdk

* This project sort to solve the challenges with sofware running on different architectures by employing decorized applications.
* With the help of internet. We were able to research enough on most technologies using decomentations and AI assistances like chatGPT 
* Challenges:
* 

### Collaborations
This is a hand-on cloud engineering project delivered by the azubi africa cloud team in 2023. After 6 months of AWS cloud training and front-end development, we got a chance to work on some realife cloud projects. 
I was able to work with:
1. Paul Timothy Wekesa Wafula [paul.timothy@azubiafrica.org]
2. Aaron Odeny [aaron.odeny@azubiafrica.org]
3. Ogunleye Emmanuel [ogunleye.emmanuel@azubiafrica.org]
7. Kelvin Michuki Mwangi [kelvin.michuki@azubiafrica.org]
##
### Project Overview
```sh
   Todo and technologies
1. Create front-end - VScode
2. Test server = xammp server locally + docker desktop
3. Use AWS Container Services
4. Push images to docker hub
4. Use AWS DynamoDB, Fargate,  
3. Launch a sample webapp locally and online

```

## Version 3 
```sh
   Task 1: Manual Dynamo Table
```
You need to have a an AWS account, you can get a freetire account which basically means you get a free 1 year to use some AWS resources. In our case, we have that setup and we will be using the dynamoDB service

* Go to your AWS Console and navigate to the DynamoDB service. 
* Click on the "Create table" button. 
* Enter "GuestBook" as the table name. 
* Enter "Email" as the primary key and make sure to select "String" as the data type. 
* Create a Country and Name Fields. You may need to research on (global and local indexes)
* Click on the "Create" button to create the table. 
* Once the table is created, click on the "Items" tab to add some sample data to the table.  
* Click on the "Create item" button and enter the sample data for the "Name", "Email", and "Country" fields. 
* Populate this with your team members info.


##
```sh
   Task 2: Link Dynamo to webpage
```
We will be working with  a new page Guestlist.php we will use php as it can process the requests in the background. Pick the template for this new file:
[https://github.com/lawrencemuema/Cloud_project02]

**There are some packages needed for us to run the connection to dynamo***
# Working with AWS SDK for php

1. Install Composer (https://getcomposer.org/), a package manager for PHP.  
2. In your project directory, run the “composer require aws/aws-sdk-php". This will install the needed packages. 
  Git error: Install git from here, https://git-scm.com/download 
3. Once the AWS SDK for PHP is installed, you can use it in your PHP code by including the Composer-generated autoloader: 
require 'vendor/autoload.php'; 
4. You are now able to call on dynamo and perform the desired functions. 

```sh
   Task 3: Using Terraform
```
To reduce redundancy and complexities we will use terraform to create our dynamo dB table.
Read: 
** A terraform file is a configuration file that defines the infrastructure and resources to be created by Terraform.**

#Using Terraform to create dynamo dB
1. Install Terraform on your local machine following the installation guide for your operating system: 
Install terraform
<!-- https://developer.hashicorp.com/terraform/downloads -->
2. Set up your AWS credentials on your local machine. You can do this by configuring the AWS Command Line Interface (CLI) using the aws configure command. 
3. Create a new directory/folder on your local machine where you will store your Terraform configuration files.  
4. Create a new file in your Terraform directory called anything.tf. or any name of your choice
5. Create a new file in your Terraform directory called anything.tf. 
6. To create a dynamo dB using a terraform file, you need to: 
 * Define the attributes and settings of the dynamo dB table, such as name, hash key, range key, read capacity, write capacity, etc. 
 * Dummy Data can be added in the same file, different file. But make sure you add the data using terraform.
7. Dummy Data can be added in the same file, different file. But make sure you add the data using terraform.
8. Run terraform plan to preview the changes that will be made
9. Run terraform apply to create the dynamo dB table 

```sh
   Task 4: Deployment
```
We will work on packaging our application
#Docker Hub Deployment

1. Create a Dockerfile in the "version3" folder with the following contents: Dockerfiles are what tell docker how it should build your image (environments)  
2. Build the Docker image using the following command:  
 ** docker build -t your-dockerhub-username/docker-web-app:3.0**
 ** This will build a Docker image with the name "your-dockerhub-username/docker-web-app" and the tag "3.0". **
3. Push the Docker image to DockerHub using the following command:  
 ** docker push your-dockerhub-username/docker-web-app:3**
 
<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/Amigo51/docker-web-app.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@my_twitter](https://twitter.com/@20pesewes) - seth.ofori-amanfo@azubiafrica.org

Project Link: https://github.com/Amigo51/docker-web-app.git]https://github.com/Amigo51/docker-web-app.git)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- References -->
## References

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://github.com/lawrencemuema/Cloud_project02)
* [Terraform Helpful links](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/dynamodb_table)
* [Terraform Helpful links](https://cloudkatha.com/how-to-create-dynamodb-table-using-terraform/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
