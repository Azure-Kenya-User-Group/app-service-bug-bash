# App Service Bug Bash – January 2025

The goal 🎯 of this bug bash is to test out Node.js deployment scenarios and ensure that users can successfully deploy a Node.js Web Application on[ Azure App Service](https://azure.microsoft.com/products/app-service/?msockid=0b50b8fa1230692c3493adb913b768eb).

## Requirements
1.	An Azure Subscription
2.	[Node.js ^18.20.5](https://nodejs.org/en) & npm
3.	[Visual Studio Code](https://code.visualstudio.com/) & [Azure App Service Extension](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azureappservice)
4.	Node.js project – Either select a sample from Microsoft, or Bring Your Own Code

## Project Selection
You can deploy your project from local or from a Codespaces.

### Option 1: Microsoft Samples
1. Follow [these instructions](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode) to create and deploy an Express web app to Azure App Service.
1. Select a complete E2E template to deploy 
1. Follow [this tutorial](https://learn.microsoft.com/en-us/azure/app-service/tutorial-nodejs-mongodb-app?tabs=copilot&pivots=azure-portal) to deploy a Node.js + MongoDB web application on Azure. 

### Option 2: Bring Your Own Code (BYOC)
- Bring your own Node.js project ready for deployment. 
- Additional resources to help you [Build JavaScript applications with Node.js](https://learn.microsoft.com/en-us/training/paths/build-javascript-applications-nodejs/)

## Deploy to Azure
_Note: [App Service Runtime Support for Node](https://github.com/Azure/app-service-linux-docs/blob/master/Runtime_Support/node_support.md#nodejs-on-app-service)_

Complete deployment either via the [App Service VS Code extension](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode#deploy-to-azure) or through the [Command-Line Interface (CLI)](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-cli#deploy-to-azure)

### Option 1: Deploy to Linux App Service
1. [Instructions](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=linux&pivots=development-environment-vscode#configure-the-app-service-app-and-deploy-code)
1. Node.js app [configuration for Azure App Service on Linux](https://learn.microsoft.com/en-us/azure/app-service/configure-language-nodejs?pivots=platform-linux) as the hosting platform.

### Option 1: Deploy to Windows App Service
1. [Instructions](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode#configure-the-app-service-app-and-deploy-code)
1. Node.js app [configuration for Azure App Service on Linux](https://learn.microsoft.com/en-us/azure/app-service/configure-language-nodejs?pivots=platform-windows) as the hosting platform.

## Re-Deployment to Azure
If you deployed initially using the VS Code extension, redeploy your changes using the [command-line interface (CLI)](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-cli#redeploy-updates)and vice versa.
Set up continuous deployment (CD) with GitHub Actions

Set up continuous deployment (CD) with [GitHub Actions](https://docs.github.com/en/actions/use-cases-and-examples/deploying/deploying-nodejs-to-azure-app-service)

## Stream Logs
Try accessing your logs using the [VS Code extension](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-vscode#stream-logs), [CLI tool](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-cli#stream-logs) or directly on the [Azure Portal](https://learn.microsoft.com/en-us/azure/app-service/quickstart-nodejs?tabs=windows&pivots=development-environment-azure-portal#stream-logs).

## Feedback Submission