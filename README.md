# azuretemplate
az group create --resource-group  rg-delo-poc --location
az deployment group create --resource-group rg-delo-poc --template-uri https://raw.githubusercontent.com/lmondelaersdev/azuretemplate/master/armdeploy.json --parameters https://raw.githubusercontent.com/lmondelaersdev/azuretemplate/master/armdeploy.parameters.json
az group delete --name rg-delo-poc