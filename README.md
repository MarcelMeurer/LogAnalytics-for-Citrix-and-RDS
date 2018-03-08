# LogAnalytics-for-Citrix

The Log Analytics Agent monitors each worker in your RDS or Citrix environment. The agent is focused on events, performance consumption, network activities and more regarding each user’s IT experiences. Workers in this context are Windows Remote Desktop Server, XenApp Servers and of course Windows Client VDI’s (XenDesktop).

The agents combine data from different sources and send them to your OMS Log Analytics workspace in Azure. There is no other infrastructure needed: No SQL server, no windows server. Nothing else! The data are saved and analyzed in Azure.

Go to http://loganalytics.sepago.com to download the agent.


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FMarcelMeurer%2FLogAnalytics-for-Citrix%2Fmaster%2FITPC-OMS-Citrix.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
