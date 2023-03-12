#Udagram Full-Stack
#Pipeline
From the root of the project:

npm run frontend:install - To install frontend dependencies.
npm run frontend:build - To build the Angular/Frontend.
npm run frontend:lint - To lint the Angular/Frontend.
npm run frontend:e2e - To e2e the Angular/Frontend.
npm run frontend:deploy - To deploy the project to S3 using deploy script.
npm run api:install - To install backend dependencies.
npm run api:build - To transpile the Typescript/Backend.
npm run api:deploy - To deploy the project to EB using deploy script.

#CircleCi
The order of the run jobs:

Setting Env Variables.
Install NodeJS.
Checkout Code & Cloning the Repo.
Install AWS CLI v2.
Check & Disable AWS pager.
Configure AWS AccessKeyID.
Configure AWS Region.

Frontend:
Install dependencies.
Build the angular.

Backend-api:
Install dependencies.
Build the app.

Deploy App:
Deploy Frontend the site to AWS S3.
Deploy api the app to AWS Elastic Beanstalk.
