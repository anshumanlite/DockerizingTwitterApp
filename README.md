# DockerizingTwitterApp
Deploying a Python Application API on a container image with the help of Docker, which can be accessed from anywhere using AWS service.


Implementation
Step1: We first created a Flask application using HTML, CSS and python.
Step2: We used 2 APIs, Tweepy through twitter developer account and Textblob
 which extract live tweets and does sentiment analysis of those tweets.
 ![image](https://user-images.githubusercontent.com/72924364/143005366-6a4b1a95-8ea7-4faf-83fc-bd7b39bdd2bc.png)

 
Step3: We dockerized this app and created the docker file. We used docker desktop
 and Vscode for this. Vscode is the IDE for coding and docker desktop is a
 software where we can run the containers and images.
 
 ![image](https://user-images.githubusercontent.com/72924364/143005407-29d24852-4b21-44c7-aab8-7fbb3ac3b19b.png)

![image](https://user-images.githubusercontent.com/72924364/143005424-3fd4f0da-ebd1-413c-bfd3-6125c5f8b41b.png)

![image](https://user-images.githubusercontent.com/72924364/143005450-f33343d9-882f-4e99-8743-ac32f72cb13f.png)


Step4: After dockerizing the app we created an account in AWS for deploying our
container on cloud.
Step5: Then we created a repository and deployed our container image in AWS ECR

![image](https://user-images.githubusercontent.com/72924364/143005489-9f33496f-3251-479c-aec2-9247fb200d08.png)


Step6: After this, we created a cluster and defined a task in AWS ECS

![image](https://user-images.githubusercontent.com/72924364/143005519-16ee44dc-cd0e-44fd-8d22-d76c39e42319.png)

Automatically a EC2 instance got created and was running.

Step7: Now we can use the public IPv4 DNS to run our app using AWS EC2.

![image](https://user-images.githubusercontent.com/72924364/143005639-2bb7e628-5a54-48d7-ac18-1434d3375031.png)

#This repo is unfinished yet . Whole code will be uploaded soon.
