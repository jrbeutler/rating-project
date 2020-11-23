# Development Environment Manual
## Setup
1. You will need to set up an account on [Azure](https://portal.azure.com/#home) where you can opt for a free account.
2. After setting up an account, you'll want to login to [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)
and create a project in your organization.
3. Click on the Repos tab, and from there use the link provided to push the backend repository.
4. Next, choose "create a pipeline," then choose "use the classic editor," and then choose "empty job."
5. Press the Agent job 1 and add two npm tasks from the search bar. Leave the first one alone, but
for the second one, rename the task "npm run build," and in the dropdown for command select "custom."
In the command and arguments section, enter "run build."
6. In Agent job 1, add a "publish artifact: drop" and change the path to publish to "build." Then click save and queue.
7. Go to [https://portal.azure.com](https://portal.azure.com) and click "Web Apps" then "Create app service."
Choose your subscription, create a new resource group name, give it a unique name, choose publish as code, choose
runtime stack "Node 10.14," choose "Windows" operating system, choose the closest region to you, and then hit review and create.
8. Go back to DevOps and to Pipelines and create a new release. 