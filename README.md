<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>



<!-- ABOUT THE PROJECT -->
## About The Project

This project is about a web application development with docker and aws services
* Version 1 - Static files on web server
* Version 2 - Verification of static form file with php 
* Version 3 - Integration with DynamoDB service on aws using php + sdk

Coloborators
* Seth Ofori – Amanfo – Project Manager
  ![image](https://user-images.githubusercontent.com/112909838/232318920-3cceae3f-c547-4550-9380-749fbab61cf1.png)

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
7. Kelvin Michuki Mwangi 
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

##
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
Webhosting is what allows o a webfile to be served to the internet. AWS offers a free option to host a static website (static is something that doesnt use data from a database).
* Go to your s3 bucket
* Go to the properties tab
* Scroll down to Static Web Hosting and enable this.
##
```sh
   3. Launch your website on s3
```
We have a bucket and its now hosting ready, all we need to do is add our files and we can access the site.
* Go to your s3 bucket and upload "objects". these are your webfiles from your computer
* Go to the s3 bucket properties tab
* Scroll down to Static Web Hosting and you should now see a url.
*click on the url and access your site.



## Showcase a simple Architecture diagram
<!-- setup a link to your images folder -->
<a href="[https://github.com/lawrencemuema/Cloud_project02](https://github.com/lawrencemuema/Cloud_project02/blob/main/images/fargate_arch.png)">
    <img src="images/fargate_arch.png" alt="Logo" width="auto" height="150">
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@my_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- References -->
## References

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
