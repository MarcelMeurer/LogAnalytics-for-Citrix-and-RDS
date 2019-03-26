# Azure Log Analytics Agent for RDS and Citrix Sites

The Log Analytics Agent monitors each worker in your RDS or Citrix environment. The agent is focused on events, performance consumption, network activities and more regarding each user’s IT experiences. Workers in this context are Windows Remote Desktop Server, XenApp Servers and of course Windows Client VDI’s (XenDesktop).

The agents combine data from different sources and send them to your OMS Log Analytics workspace in Azure. There is no other infrastructure needed: No SQL server, no windows server. Nothing else! The data are saved and analyzed in Azure.

Go to http://loganalytics.sepago.com to download the agent and learn more.

After the depoyment:
- Install and configure the agents
- Set the retention time of your workspace (default: 360 days)
- Set the DPOR number (http://loganalytics.sepago.com/installation.html)

## Deploy a full OMS workspace for RDS to your Azure subscription
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMarcelMeurer%2FLogAnalytics-for-Citrix%2Fmaster%2FITPC-OMS-RDS.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Deploy a full OMS workspace for Citrix to your Azure subscription
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMarcelMeurer%2FLogAnalytics-for-Citrix%2Fmaster%2FITPC-OMS-Citrix.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


##You can easily deploy the solution from the Azure Marketplace:
https://azuremarketplace.microsoft.com/en-us/marketplace/apps?search=sepago&page=1
