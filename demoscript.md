# Introduction: Storage Account in Azure
Storage Account in Azure provides highly scalable and available storage units which is accessible from anywhere. There are different types of storage accounts in Microsoft Azure namely : blob, file-shares, queues, tables.
There are also other attributes associated to storage accounts like
Access tiers - Hot, Cold, Archive
Redundancy - LRS, ZRS, GRS
- Hot Tier - low latency, high storage cost, better performance.
- Cold Tier - access to data upto 30 days old, less storage cost, more latency.
- Archive - access to data upto 180 days old, least storage cost, most latency. 


## Template:

![snip1](https://user-images.githubusercontent.com/24872414/85196094-5a4dc800-b2f5-11ea-8f0a-aec9bd4f8050.PNG)

![snip2](https://user-images.githubusercontent.com/24872414/85196145-b6b0e780-b2f5-11ea-8f11-3637936ef4e2.PNG)

## Deploy Azure template for storage account using cloud shell 

`az deployment group create --resource-group <resource-group-name> --template-file <path-to-template>`

## Output of Deployment of ARM template using cloud shell

![snip3](https://user-images.githubusercontent.com/24872414/85196471-0395bd80-b2f8-11ea-86d9-8ec7caededf9.PNG)

## Storage Explorer demo
We can look forward to the Storage Explorer Demo and the various types of storage we can access:

- Step 1: Copy connection string from Key 2 from Storage Account - Access Keys on the portal as shown below

![snip4](https://user-images.githubusercontent.com/24872414/85196573-a9e1c300-b2f8-11ea-9ff4-afb9cd55530b.PNG)
- Step 2: Attach the connection string to storage account explorer

![snip5](https://user-images.githubusercontent.com/24872414/85196660-66d41f80-b2f9-11ea-92f6-5b7d4faa94f0.PNG)
- Step 3: Storage Explorer Demo by blob, file, queue and table creation. (In table multiple property can be added in different records)
[
![Screenshot (12)](https://user-images.githubusercontent.com/24872414/85196669-73587800-b2f9-11ea-98ea-a9e01fa1d6fb.png)
](url)
