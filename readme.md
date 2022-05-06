# What The Hack - DevSecOps with GitHub

## Introduction
DevOps is a journey not a destination. Our goal when writing this challenged based hack is to introduce you to GitHub and some common DevOps and DevSecOps practices. We also understand that your choice of programming language and DevOps processes might differ from the ones we will be using in this hack, that is OK. Our intent was to select some of the most common programming languages and highlight industry best practices, with an emphasis on showing how GitHub can help you on your DevOps/DevSecOps journey, so that you can apply this in your environment with the languages and tools that you use.

## Learning Objectives

This DevSecOps with GitHub hack will help you learn:

1. How to use GitHub to manage source control
1. How to use GitHub for Project Management
1. How to use GitHub Actions for CI & CD

## Challenges
 - [Challenge 0](./Student/challenge00.md) - Setup and Introduction
 - [Challenge 1](./Student/challenge01.md) - Track your work with GitHub Project Boards
 - [Challenge 2](./Student/challenge02.md) - Centralize your code with GitHub Repos
 - [Challenge 3](./Student/challenge03.md) - Infrastructure as Code
 - [Challenge 4](./Student/challenge04.md) - Continuous Integration
 - [Challenge 5](./Student/challenge05.md) - Continuous Delivery
 - [Challenge 6](./Student/challenge06.md) - Security


## Prerequisites - each participant must meet the following prerequisites:
- Access to an Azure sandbox subscription with the contributor role
- Permissions to create a branch in the workshop repository after it is forked into your GitHub organization
- Permissions to create a GitHub Codespace

## Repository Contents
- `../Student`
  - Student Challenge Guides
- `../Student/Resources`
  - Student's resource files, code, and templates to aid with challenges

## Considerations

If you are running this hack with a group, here are some options for providing access to Azure:
- Each person/team uses their own subscription (ideal)
- Use a single subscription with each person/team using a different resource group
- Use a single subscription and resource group, with each person/team creating resources within the single resource group (less ideal)

Regardless of the option you choose, you'll have to consider:
- [Azure default quotas and resource limits](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits) (for example, # of VMs allowed per region or subscription)
- Unique naming of resources - many services may require a globally unique name, for example, App service, container registry.

## Contributors
- Kevin M. Gates
- Will Fox
- Julia Nathan
- Jim Blizzard