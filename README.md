# Node-RED for Azure Web App
 This repository is Node-RED for Azure Web App. You can easily deploy it to Azure Web App using the following deploy button.
 
<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fzuhito%2Fnode-red-webapp%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a><br><br>

This Node-RED includes nodes for Azure services.
- node-red-contrib-azure-documentdb
- node-red-contrib-azure-https
- node-red-contrib-azure-table-storage
- node-red-contrib-azure-blob-storage
- node-red-contrib-cognitive-services
- node-red-contrib-azure-sql
- node-red-contrib-azureiothubnode

![node-red](https://raw.githubusercontent.com/zuhito/node-red-webapp/master/nodered.png)

# Deploy to Azure Web App
(1) Click deploy buttion

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fzuhito%2Fnode-red-webapp%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a><br><br>

(2) Input resource group, site name and hosting plan name.

![azure_setting1](https://raw.githubusercontent.com/zuhito/node-red-webapp/master/azure_setting1.png)

(3) After deployment, enable websocket and always on.

![azure_setting2](https://raw.githubusercontent.com/zuhito/node-red-webapp/master/azure_setting2.png)
