# Udagram App infrastructure

Udagram app is full stack application connected to a postgresql database and hosted on AWS

## AWS components and how it run udagram app

1- Simple Storage Service (s3) bucket which is an object-based storage service containing udagram frontend and providing the UI experience to the final users by providing the the frontend content publicly throug a URL which is:
http://tabdullah-udagram.s3-website-us-east-1.amazonaws.com 

2- Elastic Beanstalk which creates a production environment providing all infrastruce needed for our backend component of udagram app to run.Elastic Beanstalk is integrated with S3 to serve the backend functionality to the frontend component on S3.

We can run the backend component alone by visiting the following URL:Udagramserver-env.eba-bpp53agj.us-east-1.elasticbeanstalk.com

2- Relational Database Service (RDS) providing us with a postgresql database on which backend depends to store,manipulate and retrieve data.

Database URl:database-1.cvjsclrvf63s.us-east-1.rds.amazonaws.com