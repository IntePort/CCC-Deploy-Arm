
# CCC- DeployToAzure


<a href="https://azuredeploy.net/" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/101-data-factory-blob-to-sql-copy/azuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
    
    
When you deploy this Azure Resource Template, a data factory is created with the following entities: 

- Azure Storage linked service
- Azure SQL Database linked service
- Azure Blob dataset
- Azure SQL dataset
- Pipeline with a copy activity 

The copy activity in the pipeline copies data from an Azure blob to an Azure SQL database. You should see a diagram similar to the following one in the diagram view of the data factory.  

![Diagram view](images/adfDiagram.PNG)

