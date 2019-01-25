# Deployment of workshop environment.

<!--<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FArthurCh%2FAppWorkshop%2Fmaster%2FIaaS2PaaSWeb%2FEnvironments%2FWorkshopEnv.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
-->



This allows you to deploy the workshop environment.  When complete, you should have a Web Server and SQL server fully configured in their own vNet and Resource group.

## Prerequisites

Create a resource group.  The deployment will require an existing resource group the the Azure subscription

## Deployment steps

Execute the AzCLI commands int eh arm-deployment-script.azcli file

Optional: Enter vm admin username and password

You can leave default values for the other parameters

NOTE: do not change the value of _artifactsLocation or _artifactsLocationSas as the deployment will fail.
