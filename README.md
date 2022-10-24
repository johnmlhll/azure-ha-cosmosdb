# azure-ha-cosmosdb
This infrastructure oriented repo is for the sole purpose of deploying a H/A deployment of a cosmos account and a DocumentDB (NoSQL) managed database into a Maolte demo subscription on Azure from Azure DevOps CICD pipeline via secure connection. Nothing more to see here save a highly available multi region cosmosDB account deployment (westeurope/northeurope) using Azure's IaC ARM (JSON) template with a parameters file and secrets deployed from Azure KeyVault via ARM service connection. Some optional triggers/stored procedures to test the managed database is also coded for thoroughness sake to validate the deployment. Also, wanted to see how the API handled free tier enablement for cosmosdb account as a managed Azure service.

Also of note is the trialing of Azure's new API version 2022-15-05 to see if its works despite MS Code linter not recognising it. This exploratory IaC repo is for demo purposes only but is reusable as IaC once you configure your sub with the appropriate key vault values.

# Maolte Technical Solutions Limited 
This repo is the 2nd in a series of demo deployments for the company I set up to pursue contracting. My intent for these repos is to demo my CICD skills mainly in infrastructure deployments over time and in segments. The idea is to show case reusable infrastructure as code (IaC) for cloud resources via ARM templating in Azure and CloudFormation templating in AWS. I will time permitting code up some fun apps for demo purposes and demo infrastructure as I go. 

Maolte Technical Solutions Limited was set up provide specialist services in the Cloud Infrastructre, DevOps and Writing. More at https://maolte.ie. Any queries, drop me a long at john@maolte.ie.

Best Regards
John

Founder | Engineer | Writer
Maolte Technical Solutions Limited