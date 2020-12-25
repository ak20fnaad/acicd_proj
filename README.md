Overview
This project is to build a Github repository and create a scaffolding that will assist in performing both Continuous Integration and Continuous Delivery. 
It uses Github Actions along with a Makefile, requirements.txt and application code to perform lint, test, and install. Then it integrates it with Azure Pipelines to enable Continuous Delivery to Azure App Service.

Project Plan
A Trello board for task tracking as well as a spreadsheet with estimated project plans are usually used for the planning.
Note: Appologies for the screenshots provide here are those used for the excercise, just to show the effort. (unfortunately the local files used for the project were lost)  
A sample Trello board link:  https://trello.com/b/ZY7koOQO/nnanoproj (a screen shot will also be included)
A sample project spreadsheet:The spreadsheet is local, scrrnshot will be included


Instructions
1. Setting up Azure Clou Shell for Continuous Intigration(CI)
  This is to set up a cloud-based development structure using Azure Cloud Shell creating  a Makefile, tests, and application scaffolding.  
  Once this step is completed the code can be tested locally in the Azure Cloud Shell. 
  This is a local continuous integration step. 
  All Python that is created should have a local continuous integration setup as well as a remote build server that runs the same code. 
  
  The steps included:  
      a)To create the Cloud-Based Development Environment:
          i)Create a GitHub Repo
          ii)Launch Azure Cloud Shell environment
          iii)Create ssh-keys, and upload them to the GitHub account
          
      b) To create Project Scaffolding, after the environment is set up the following need to be done
          i)Create the Makefile,
          ii)requirements, 
          iii) the Python virtual environment
          iv)script and test files
          
      c)Doing a local test to run the make file
          Run make all      
          
2. Configuring GitHub Actions for Continuos Integration(CI)
   This is for configuring GitHub Actions to test the project upon change events in GitHub. 
   It is a necessary step to perform Continuous Integration remotely.
   
   The steps included:
      a)Enable Github Actions from the account in GitHub UI
      b)Upadte yml code as required 
      c)Verify remote test pass in Github Actions UI

3. Setting up Continuous Delivery in Azure
  This is for setting up Continuous Delivery using Azure technologies. 
  It should involve setting up Azure Pipelines for deployments (in this case,  to deploy the Flask starter code  (provided) to Azure App Services). 
  
  The steps included: 
      a)Authorizing and enabling Azure App Service (in this case)
      b)Enabling contoinuous deployment with Azure Pipelines
      c)Checking YMAL based config file into Github
      d)Enabling Github and Azure Pipelines
      e)Deploying to Azure pipelines
      f)Verify Prediction with starter code (in this case)


Note: Afile screenshots will be included.
