# Deployment Environment Manual
## Setup
1. You will need to set up an account on [Azure](https://portal.azure.com/#home) where you can opt for a free account.
2. After setting up an account, you'll want to login to [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)
and create a project in your organization.
3. Click on the Repos tab, and from there use the link provided to push the frontend repository.
4. Next, choose "create a pipeline," then choose "use the classic editor," and then choose "empty job."
5. Press the Agent job 1 and add two npm tasks from the search bar. Leave the first one alone, but
for the second one, rename the task "npm run build," and in the dropdown for command select "custom."
In the command and arguments section, enter "run build."
6. In Agent job 1, add a "publish artifact: drop" and change the path to publish to "build." Then click save and queue.
7. Go to [https://portal.azure.com](https://portal.azure.com) and click "Web Apps" then "Create app service."
Choose your subscription, create a new resource group name, give it a unique name, choose publish as code, choose
runtime stack "Node 10.14," choose "Windows" operating system, choose the closest region to you, and then hit review and create.
8. Go back to DevOps and to Pipelines and create a new release. Choose deploying choice "Azure App
Service Deployment." Then give the stage a name. Click "add artifact" and choose your pipeline and artifact that was generated
when you ran the pipeline. Once set, press the button "Add" to add the artifact.
9. Click on the "1 job, 1 task" under your stage and select the "Deploy Azure App Service" task. Press manage
and choose "Create service connection", then "Azure Resource Manager."
- Connection name: name it your Azure subscription to keep track of it.
- Select the appropriate subscription
- Select the Resource group that has your "app service"
10. Go back to the release tab and set the following:
- Display name: Azure App Service Deploy: ratings-project
- Connection type: Azure Resource Manager
- Azure Subscription: select the one you used previously
- App Service type: Web App on Windows
- App Service name: ratings-project
- Package or folder: use given
11. Create the release from the pipeline and visit the Azure WebApp URL to see your website!
