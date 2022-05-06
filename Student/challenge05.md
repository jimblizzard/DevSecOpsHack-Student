# DevSecOps with GitHub workshop

## Challenge 5 – Continuous Delivery (CD)

[< Previous](challenge04.md) - [Home](../readme.md) - [Next >](challenge06.md)

### Introduction

In DevOps after we automate our build process, we want to automate our release process, we do this with a technique called Continuous Delivery (CD). Please take a moment to review this brief article talking about why this is important. 

- [What is Continuous Delivery?](https://docs.microsoft.com/en-us/azure/devops/learn/what-is-continuous-delivery)

### Challenge

In this challenge, we will use GitHub Actions to deploy our application to the dev environment. 

Use your Codespaces environment to update your workflow file then commit and push any changes.

Extend the workflow you created in Challenge #4 to:

1. Use the `Azure/webapps-deploy@v2` [action](https://github.com/Azure/webapps-deploy) to update the Web App 

2. Make a small change to your application  (i.e.,`/Application/aspnet-core-dotnet-core/Views/Home/Index.cshtml`), commit, push, monitor the workflow and see if the change shows up on the dev instance of the website.

**NOTE**: Normally, we would have you configure [release gates](https://docs.microsoft.com/en-us/azure/devops/pipelines/release/approvals/?view=azure-devops) next - which would require some type of manual approval/human intervention *before* deploying to test and prod respectively.

### Success Criteria

1. A small change to `/Application/aspnet-core-dotnet-core/Views/Home/Index.cshtml` automatically shows up on the website running in the dev environment (i.e., `<prefix>devops-dev`.azurewebsites.net).

### Learning Resources

- [Deploy a web app to App Service using GitHub Actions](https://docs.microsoft.com/en-us/azure/app-service/deploy-github-actions?tabs=userlevel#set-up-a-workflow-manually)

[< Previous](challenge04.md) - [Home](../readme.md) - [Next >](challenge06.md)
