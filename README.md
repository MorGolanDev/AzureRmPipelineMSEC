# **AzureRmPipelineMSEC**

## **Project Description**

### In this project I implemented below:
- ARM templates for 2 Storage accounts. 
- ARM template for Windows Server.
- Self-hosted agent to run Azure DevOps Pipeline.
- Azure DevOps Pipeline to build and deploy the Storage accounts and Windows server in continous manner (CI/CD).
- Script that create, upload and copy 100 blobs from Storage account A to Storage account B, executed on the Windows server as part of  above CD pipeline tool.
- Monitor Dashboard for the described system.

Storage Account Azure DevOps Pipeline [![Build Status](https://dev.azure.com/morgolan10/AzureRmPipelineMSEC/_apis/build/status/MorGolanDev.AzureRmPipelineMSEC?branchName=main)](https://dev.azure.com/morgolan10/AzureRmPipelineMSEC/_build/latest?definitionId=16&branchName=main)

![Virtual Machine](https://github.com/MorGolanDev/AzureRmPipelineMSEC/blob/main/images/vm.jpg?raw=true)
![Storage Account](https://github.com/MorGolanDev/AzureRmPipelineMSEC/blob/main/images/storageaccount.jpg?raw=true)


### **Infrastructure as Code (IaC)**
Infrastructure as Code (IaC) is the management of infrastructure in a descriptive model. Using IaC model generates the same environment every time it is applied.

#### **Using IaC on Azure**
Azure provides native support for IaC via the Azure Resource Manager. Teams can define declarative templates that specify the infrastructure required to deploy their solutions.

### **ARM – Azure Resource Manager**
Azure Resource Manager is the deployment and management service for Azure. It provides a management layer that enables you to create, update, and delete resources in your Azure account.

#### **Resource & Resource Group**

  ##### **Resource** - A manageable item that is available through Azure. Virtual machines, storage accounts, web apps, databases, and virtual networks are examples of resources. Resource groups, subscriptions, management groups, and tags are also examples of resources.
  ##### **Resource Group** - A container that holds related resources for an Azure solution. The resource group can include all the resources for the solution, or only those resources that you want to manage as a group.

### **ARM Templates**
A JavaScript Object Notation (JSON) file that defines one or more resources to deploy to a resource group, subscription, management group, or tenant. The template can be used to deploy the resources consistently and repeatedly.

### **Storage Account**
An Azure storage account contains all of your Azure Storage data objects, including blobs, file shares, queues, tables, and disks.

### **Windows Server**
Windows Server is the platform for building an infrastructure of connected applications, networks, and web services, from the workgroup to the data center.

### **Azure Pipelines agents**
To build your code or deploy your software using Azure Pipelines, you need at least one agent.

#### **Self-hosted agents**
An agent that you set up and manage on your own to run jobs is a self-hosted agent. You can use self-hosted agents in Azure Pipelines or Azure DevOps Server.

### **Azure Dashboards**
Azure dashboards are useful in providing a single pane of glass over your Azure infrastructure and services. While a workbook provides richer functionality, a dashboard can combine Azure Monitor data with data from other Azure services.