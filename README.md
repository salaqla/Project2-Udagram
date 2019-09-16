# Sami Alaqla - Udagram Image Filtering Microservice project

###  Education project from Udacity - Cloud Developer Nanodegree Program -  Project 2 Udagram
###  In this project I develop a cloud-based application for uploading and filtering images








#  Tasks that are done

### Engineering Process and Quality

1. All project code is stored in a GitHub repository and this link has been submitted for review. There are at least two branches - one for development (dev, development) and one master. Master should contain the most up-to-date, stable code at the time of submission.

2. Any variables use typescript typing wherever possible, variable and function names are clear, endpoints are logically named. Good coding practices are followed.


### Development Server

1. Starting the server with npm run dev runs a local instance of the server with no errors

2. The stubbed @TODO1 endpoint in src/server.ts is completed and accepts valid requests including:
localhost:8082/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg

3. Successful responses have a 200 code, at least one error code for caught errors (i.e. 422)

(Steps to run localy)
1. Initialize a new project: "npm i".
2. run the development server with "npm run dev".


### Elastic Beanstalk Deployment

1. The project was deployed using the AWS Elastic Beanstalk CLI eb init, eb create, and eb deploy commands.

2. A screenshot of the elastic beanstalk application dashboard is included in a deployment_screenshot directory.

3. An endpoint URL for a running elastic beanstalk deployment (EB_URL) has been submitted along with the project submission. This endpoint responds to valid GET requests including:

(Steps to Deploying in EB system)
1. Type "eb init" to initialize ElasticBeanstalk. 
2. Type "eb create" to create new environment to deploy our image-filter service.
3. Type "eb deploy" to push changes.

### GitHub repository

https://github.com/salaqla/Project2-Udagram.git


### AWS EB Endpoint
http://project2-udagram2-dev.us-east-1.elasticbeanstalk.com/

test picture
http://project2-udagram2-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://timedotcom.files.wordpress.com/2019/03/kitten-report.jpg
