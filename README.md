# DAT221x Introduction to NoSQL Data Solutions Lab #2
This is a fixed code for Microsoft's edX course DAT221x Introduction to NoSQL Data Solutions (https://www.edx.org/course/introduction-to-nosql-data-solutions-2) Lab #2 asset-tracking web app.

**documnetdb** branch is build as the original project on *.NET Framework 4.6.2* and works only being deployed via MS Visual Studio 2017/2019 (Communinity Edition).
**CosmosDB** is build on *.NET Framework 4.7.2.* and supports continuous deployment with GitHub.

Deployment using Visual Studio (**documnetdb**, **CosmosDB**):
1. Open the project in Microsoft Visual Studio.
2. Publish it to your Azure web app or create a new one (Azure App ASP-CosmosDB-b401 (F1: Free) service plan should be enough).
3. Open the web app via a link in the Owerview section.

Deployment using Azure App services Deployment center (**CosmosDB** only):
1. Create an empty App service instance using Azure portal - https://docs.microsoft.com/en-us/azure/app-service/ (Azure App ASP-CosmosDB-b401 (F1: Free) service plan should be enough).
2. Configure continuous deployment with GitHub via Deployment Center - https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment#deploy-continuously-from-github
