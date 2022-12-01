> ## steps and configurtation for CI/CD
1. followed given installation steps and resolved dependencies issues and used the required versions of the libraries .
2. created a database and built the backend and front end and made sure the database works .
3. created the database using RDS and tested the connection using postbird.
4. created s3 bucket and edited the bash file and package.json with the newely created s3 bucket name and ran the script and checked that it gets uploaded correctly .
5. created the application and its environment on elastic beanstalk . 
6. added environmental variables to aws elasticbeanstalk environment and modified the deployment script and pakage.json to point to the correct environment  .
7. pushed my local repo to github and connected it with circleci.
8. added the environmnet variables needed for aws authetication to circleci .
9. configured the config.yml file and added teh jobs needed to ensure that everything works correctly .
10. checked that whatever modifications i add to the code on my local repo propagates to the project hosted online.

>### aws services used:
* RDS for creating relational database.
* S3 for hosting frontend .
* Elastic Beanstalk to host backend server.


> ### important links 

-> github repo link : https://github.com/AhmedAbdelhady24/udagram

-> front end link http://udagram3011.s3-website-us-east-1.amazonaws.com/

-> backend end link http://udagramapi-env-1.eba-pyf5pxip.us-east-1.elasticbeanstalk.com/

-> database link database-1.c2c5cmdyl6kq.us-east-1.rds.amazonaws.com
