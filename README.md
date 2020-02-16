# Azure Monitor for RDS, Windows Virtual Desktop and Citrix Sites

This solution monitors each worker in your RDS, WVD or Citrix environment. The agent is focused on events, performance consumption, network activities and more regarding each user’s IT experiences. Workers in this context are Windows Remote Desktop Server, Windows Virtual Desktop, XenApp Servers and of course Windows Client VDI’s (XenDesktop).

The agents combine data from different sources and send them to your OMS Log Analytics workspace in Azure. There is no other infrastructure needed: No SQL server, no windows server. Nothing else! The data are saved and analyzed in Azure.



Go to [http://loganalytics.sepago.com](http://loganalytics.sepago.com) to download the agent and learn more.



After the deployment:

- Install and configure the agents
- Set the retention time of your workspace (default: 360 days)
- Test the agent and Azure Monitor
- Analyze your data
- Decide if you will continue the Azure Monitor Agent in the community edition or if you want to run fully supported, including premium features, updates, and support for building KUSTO queries. Visit [sepago Shop](https://shop.sepago.de/product/?id=1E79F2B5-7514-4AEB-B092-63365BBAAE1E) for more information.



## Deploy a full Azure Monitor workspace for RDS and Windows Virtual Desktop to your Azure subscription

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMarcelMeurer%2FLogAnalytics-for-Citrix%2Fmaster%2FITPC-OMS-RDS.json" target="_blank">
​    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

## Deploy a full Azure Monitor for Citrix to your Azure subscription
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMarcelMeurer%2FLogAnalytics-for-Citrix%2Fmaster%2FITPC-OMS-Citrix.json" target="_blank">
​    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>



## **New:** Deploy the Azure Monitor solution directly from the Azure Marketplace:

[Azure Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/apps?search=sepago%20gmbh)