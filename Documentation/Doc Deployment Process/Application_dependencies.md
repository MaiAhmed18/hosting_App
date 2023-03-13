#Udagram Full-Stack
#Dependencies
- Node v14.15.1 (LTS) or more recent.
- npm 6.14.8 (LTS) or more recent.

- AWS CLI v2.

- AWS EB CLI.

- AWS RDS database running Postgres.

- AWS S3 bucket for Frontend.

- AWS Elastic Beanstalk for Backend.

#AWS Cloud Setup
RDS - Database Host:  mai-aws.chyjrf1cojva.us-east-1.rds.amazonaws.com

RDS - Database Port: 5432

RDS - Database Name: postgres

S3 Endpoint - Frontend: https://hostingppbucket.s3.amazonaws.com/home

Elastic Beanstalk URL - Backend: http://udagram-api-dev.us-east-1.elasticbeanstalk.com/

#Environment Variables
Setup the following variables in the set_env.sh file or in the cloud environments:

- POSTGRES_HOST       = <Database_IP_Address>
- POSTGRES_DB         = <Database_Name>
- POSTGRES_USERNAME   = <Database_Username>
- POSTGRES_PASSWORD   = <Database_Password>
- AWS_REGION          = <us-east-1>
- AWS_PROFILE         = <Profile>
- AWS_BUCKET          = <Bucket_Name>
- JWT_SECRET          = <your secret>
- URL                 = <Url>
- AWS_ACCESS_KEY_ID   = <AWS_ACCESS_KEY_ID>
- AWS_SECRET_ACCESS_KEY = <AWS_SECRET_ACCESS_KEY>
- AWS_DEFAULT_REGION  = <AWS_DEFAULT_REGION>
