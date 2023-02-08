### Udagram 
This is the 4th project of Udacity full stack Nanodegree, which is hosting and deploying an application that is built with:
- Angular
- Nodejs
using AWS services and CircleCi.


### AWS Services 
Three of AWS services were used in this project: 

## First: RDS 
 Creating a PostgreSQL database using AWS RDS, to store user credentials
 database: database-1.ce4vcxez7gb0.us-east-1.rds.amazonaws.com

 ## Second: Elastic Beanstalk
 Elastic Beanstalk is a service that was used in the project  to run web applications on the aws cloud by uploading the application as a zipped file to it, some configuration needs to be done in order the app to run 
 URL: udagram-api-dev.eba-jgdtezqi.us-east-1.elasticbeanstalk.com

## Third: S3 Bucket
- S3 bucket is used to contain our frontend files
- S3 bucket is used as a placeholder for our images
 URL: http://udagram-udacity.s3-website.us-east-2.amazonaws.com/

## Lets have a simple demo !

1- logged in into an existing user 
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.18.42%20PM.png)
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.18.42%20PM.png)
2- create post by choosing image and caption
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.19.11%20PM.png)
3- image added sucessfully to our feed
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.19.38%20PM.png)
4- register new user
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.20.53%20PM.png)
![img](project-screenshots/DEMO/Screen%20Shot%202023-02-08%20at%2010.34.32%20PM.png)

## Screenshots are provided in other folders
- Architecture diagram and description -> deployment/Docs/architecture
- Pipeline diagram and description -> deployment/Docs/pipeline
- Dependencies -> deployment/Docs/dependencies.md
- AWS S3 -> deployment/project-screenshots/AWS/S3 
- AWS RDS -> deployment/project-screenshots/AWS/RDS
- AWS EB -> deployment/project-screenshots/AWS/EB
- CircleCI -> deployment/project-screenshots/CirCleCI