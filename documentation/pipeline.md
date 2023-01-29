# Pipeline Process
### Trigering circleci :

A developement team push their code to github connected to circleci and that triggers circleci. 



### Circleci depends on yml config which specifie the environment,excutor and steps to perform CI/CD as follows:



* circleci imports orbs which are:
   - node.js
   - AWS cli
   - elastic beanstalk cli

* then it sets a docker image as an executer and install orbs.
* then it runs the steps of installing the dependencies, building and deploying of frontend and backend as follow:
   - installing frontend dependencies
   - installing backend dependencies
   - buidling frontend component 
   - buidling backend component 
   - deploying frontend component to S3
   - deploying backend component to elastic beanstalk