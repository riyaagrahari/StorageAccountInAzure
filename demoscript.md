# Storage Account in Azure

## Introduction: 
Storage Account in Azure provides highly scalable and available storage units which is accessible from anywhere. There are different types of storage accounts in Microsoft Azure i.e. Blob, File shares, Queues, Tables. There are also other attributes associated to storage accounts like Access tiers (Hot, Cold, Archive) and Redundancy (LRS, ZRS, GRS)

## Steps to Deploy Azure Storage Account using ARM Template:

### Template:

ARM Templates are Azure Resource Manager Templates which are written in declarative format and includes JSON objects.
We will now be deploying storage account in Azure with Standard LRS as redundancy type using the template below:

![snip6](https://user-images.githubusercontent.com/24872414/85270654-417d1800-b497-11ea-9271-c46e891a9f2f.PNG)


### Connecting Azure CLI from Azure Cloud Shell for ARM Template deployment of Storage Account

- Step 1: Go to Azure Portal and select Cloud Shell option from the portal.
- Step 2: Select Azure CLI option from the cloud shell.
- Step 3: Run the following command to deploy storage account.

`az deployment group create --resource-group <resource-group-name> --template-file <path-to-template>`

### Output of Deployment of ARM template using cloud shell

![snip3](https://user-images.githubusercontent.com/24872414/85196471-0395bd80-b2f8-11ea-86d9-8ec7caededf9.PNG)

## Connecting the Storage Account using Azure Storage Explorer demo
We can look forward to the Storage Explorer Demo and the various types of storage we can access:

- Step 1: Copy connection string from Key 2 from Storage Account - Access Keys on the portal as shown below

![snip4](https://user-images.githubusercontent.com/24872414/85196573-a9e1c300-b2f8-11ea-9ff4-afb9cd55530b.PNG)
- Step 2: Attach the connection string to storage account explorer

![snip5](https://user-images.githubusercontent.com/24872414/85196660-66d41f80-b2f9-11ea-92f6-5b7d4faa94f0.PNG)
- Step 3: Storage Explorer Demo by blob, file, queue and table creation. (In table multiple property can be added in different records)
[
![Screenshot (12)](https://user-images.githubusercontent.com/24872414/85196669-73587800-b2f9-11ea-98ea-a9e01fa1d6fb.png)
](url)
