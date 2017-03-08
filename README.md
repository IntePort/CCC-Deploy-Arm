# CCC- DeployToAzure


<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-data-factory-blob-to-sql-copy%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F101-data-factory-blob-to-sql-copy%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

When you deploy this Azure Resource Template, a data factory is created with the following entities: 

- Azure Storage linked service
- Azure SQL Database linked service
- Azure Blob dataset
- Azure SQL dataset
- Pipeline with a copy activity 

The copy activity in the pipeline copies data from an Azure blob to an Azure SQL database. You should see a diagram similar to the following one in the diagram view of the data factory.  

![Diagram view](images/adfDiagram.PNG)

