# Asterdio Incorporated

![logo](https://asterdio.com/wp-content/uploads/2022/06/asterdio-light.png)

  

This repository will be used as a template to initialize any new projects in the organization.    The template contains:

* CI/CD pipeline template

* Pull_Request template

You can remove the above section and add these following into the readme

 - Project Name: {{Name of the Project}}
 - Languages or Frameworks Used: 
 - How to deploy?

***

> Note: If you are working on API or backend related development, Please
> provide a route of /api/monitor or some any routes for the DevOps team
> to monitor the API

***

## Branching Conventions

 - Main
* Staging: Used for deployment in staging environments 

* Production: Used for deployment in production environments 


  

The three branches should be created in all repositories in the organization.

  ***

## Rules to be followed while pushing to the repositories:

 - Please review for any secrets or configuration files before pushing to the repository. Do not push it. 
 - Please use .env files for configuration and push a env file template. It will be easier for managing envs in different environments 
 - The production and staging branch are protected so ****please create a PR to merge into those branches and do not directly push into those branches.****
 - The CI/CD pipeline will be implemented in the **staging** and **production** branches.
 -  The deployment status will be notified through the **actions** tab on the repository page.
 - Always provide in brief about the commits pushed while creating a pull request to the branch
  
  ***

> *Please create a pull request to the main branch if you think there are any other trivial things to be added in the template. 
> This template is created to follow the best practices while pushing to the repositories*

***