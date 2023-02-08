
### CircleCi pipeline process

Pipeline is configure through a repository that is connected to CircleCi

### Process

Pipeline goes through 3 stages: 

1- Build that contains the following jobs that are specified in confg.yml:
   - Preparing environment variables 
   - Installing Nodejs
   - Installing frontend and backend dependencies
   - Building frontend and backend
2- Hold: 
   - Requires approval 

3- Deploy that contains the following:
     - eb/setup
     - aws-cli/setup
     - checkout
     - run: which triggers the deploy command for both backend and frontend-
         