### Storage Account demonstrations

#### Create a storage account using PowerShell 

Use the following code to create a storage account using PowerShell. Swap out the storage types and names to suit your requirements. 
```PowerShell
Get-AzLocation | Select Location  $location = "westus"  
$resourceGroup = "storage-demo-resource-group"  
New-AzResourceGroup -Name $resourceGroup -Location $location  
New-AzStorageAccount -ResourceGroupName $resourceGroup -Name "storagedemo" -Location $location -SkuName Standard_LRS -Kind StorageV2 
```
#### Create a storage account using Azure CLI 
Use the following code to create a storage account using Azure CLI. Change the storage types and names to suit your requirements. 
```bash
az group create --name storage-resource-group --location westus 
az account list-locations --query "[].{Region:name}" --out table 
az storage account create --name storagedemo --resource-group storage-resource-group --location westus --sku Standard_LRS --kind StorageV2
```
