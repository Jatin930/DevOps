# **2048 Game Deployment on Elastic Beanstalk with Docker**

## In this project, I successfully containerized the renowned 2048 game using Docker and deployed it to the Elastic Beanstalk service on AWS. This allowed for efficient and scalable deployment of the game while leveraging the benefits of containerization.

## Technologies and Concepts Utilized
_During this project, I gained valuable experience and knowledge in the following areas:_

### Docker
* Created a Dockerfile to define the container's environment and dependencies.
* Used various Docker commands to build and manage Docker images and containers.
* Utilized Docker to package the 2048 game code and its dependencies into a portable and reproducible container.
  
### AWS Elastic Beanstalk
* Created an application and environment within Elastic Beanstalk to facilitate the deployment process.
* Leveraged Elastic Beanstalk's automated provisioning and scaling capabilities, streamlining the deployment of the 2048 game.
* Utilized the features of Elastic Beanstalk, including load balancing, auto-scaling, and health management, to ensure a highly available and easy deployment.

### IAM Roles and EC2 Instance
* Created an IAM role with specific permissions to secure the resources accessed by the Elastic Beanstalk environment.
* Configured and launched an EC2 instance to support the Elastic Beanstalk deployment, providing a scalable and reliable infrastructure for the game.

## Accessing the Deployed Game
To experience the deployed 2048 game, please access the following URL:

http://jatins2048container.us-east-1.elasticbeanstalk.com/

**Please note that due to the limitations of my AWS account, this URL may not be available indefinitely. However, it serves as a testament to the successful deployment of the game using Elastic Beanstalk and Docker.**

Feel free to explore my containerized version of the 2048 game. Also you can view my Dockerfile and lookover the comments I have left there to get an explanation of it and hopefully learn something new.


### Below are some screenshots I took while working on this project:
<br>
Creating Environment and Application with Elastic Beanstalk
<br><br>
<img width="700" alt="Screen Shot 2023-07-14 at 11 59 36 PM" src="https://github.com/Jatin930/DevOps/assets/104586736/38ea93ff-faa4-4cec-b4ba-5fad629640a9">

<img width="700" alt="Screen Shot 2023-07-04 at 9 31 08 PM" src="https://github.com/Jatin930/DevOps/assets/104586736/8272dd2c-4fc3-4be6-8f2f-042723f0d76f">

<br><br>
Configuring EC2 Instance
<br><br>
<img width="700" alt="Screen Shot 2023-07-04 at 10 26 57 PM" src="https://github.com/Jatin930/DevOps/assets/104586736/28a346b8-08b9-4ba0-aa41-ceb4fc060823">

<br>
<br>

As you can see, I am not very good at this game
<br><br>
<img width="700" alt="Screen Shot 2023-07-14 at 11 53 10 PM" src="https://github.com/Jatin930/DevOps/assets/104586736/a6d87bb7-d09b-4a88-a42e-461b7d60f7c5">




