# DAT221x Introduction to NoSQL Data Solutions Lab #2
This is a fixed code for Microsoft's edX course DAT221x Introduction to NoSQL Data Solutions (https://www.edx.org/course/introduction-to-nosql-data-solutions-2) Lab #2 asset-tracking web app.

**CosmosDB** is build on *.NET Framework 4.7.2.* and supports continuous deployment with GitHub.
**documnetdb** branch is build as the original project on *.NET Framework 4.6.2* and works only being deployed via MS Visual Studio 2017/2019 (Communinity Edition).

Deployment using Azure App services Deployment center (**CosmosDB** only) open this link - https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAlexYash%2Fasset-tracking%2FCosmosDB%2Fdeploy%2Farmdeploy.json - to deploy all necessary resources and a web app code into your Azure subscription via this Azure Resource Manager template - https://github.com/AlexYash/asset-tracking/blob/CosmosDB/deploy/armdeploy.json (you don't need to run this template manually, just open the link mentioned earlier).
