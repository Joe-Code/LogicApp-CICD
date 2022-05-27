# Introduction 
This repo contains files for deploying two consumption resource type logic apps, the requesting logic app workflow calls the responding logic app workflow. Both logic apps are deployed to the same subscription.

# Getting Started
To get the code up and running on your own system, these are the steps you will need to take.

1. In Azure, create a resource group you want to use.
2. In Azure DevOps Services, create a service connection scoped to the resource group.
3. In Azure DevOps Services, create a Pipeline that uses the azure-pipelines.yml
4. Add variables to the pipeline for:
    1. ServiceConnectionName
    2. SubscriptionID
	3. ResourceGroupName
5. Run the pipeline.
