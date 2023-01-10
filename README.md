# CICD


Continuous Integration and Continuous Delivery 
--> refers to the Software Development Lifecycle 


Continuous Integration (focuses on safe and regular integration of code) 
--> development practice that requires developers to integrate code into a shared repository several times a day 
- Code is verified by an automated build to detect problems early 
- When code is written and pushed to the master brand in a repository (e.g. GiHhub or GitLab), the code is analysed and given a series of automated tests. 
  - These tests make sure logic of code makes sense, code is formatted correctly and it fulfills the scope of the project
  - e.g. tests are: 
  1. Unit Testing: tests individual units of source code
  2. Validation Testing: makes sure software satisfies its intended use 
  3. Format Testing: checks for syntax and other formatting errors 
- Every major development team has a CICD workflow 
- Allows for remote teams to collaborate on the same project 
- Popular CICD Environments: Jenkins, Circle CI, Gitlab, GitHub Actions, Team City 
- CICD prevents technical debt, automates testing processes and fixes errors early 



Continuous delivery (focuses on frequency of deployment) 
  - AFter code is tested and built using the Continuous Integration process, continuous delivery ensures code can be packaged with everything it needs to deploy to any environment at any time 
  - CD can involve provisioning the infrastructure to deploying the application to testing or the production environment 
  - CD allows software to be deployed to production at any time 
    - These deployments can be triggered manually or automatically using continuous deployment. 
    - Continuous Development is where DevOps teams set the criteria for code releases ahead of time and code is deployed when those criteria are met and validated 
  - Companies can develop features within minutes using CICD


CICD Workflow
1. Source code management(e.g Github or gitlab) is used to write code 
3. Application is built 
  - A Unit test can be added to the build pipeline 
5. Release pipeline deploys the app e.g. to a web server 
  An integration test and/or UI test can be added to the release pipeline
- Some pipelines have several pipelines 

Benefits of CICD
- Shorter Cycle Time (time it takes to delover a functional application)
- Happier employees 
- Gets to jmarket faster (code that is in production is making money, code sitting on a harddrive is not) 


https://youtu.be/M4CXOocovZ4 
https://about.gitlab.com/topics/ci-cd/ 
