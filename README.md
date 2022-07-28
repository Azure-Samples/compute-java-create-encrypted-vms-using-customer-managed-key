---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Compute
  platforms: java
---

# Getting Started with Compute - Create Virtual Machine Encrypted Using Customer Managed Key - in Java #


  Azure Compute sample for managing virtual machines -
  - Create key vault and key
  - Create disk encryption set
  - Grant disk encryption set access to the key vault by defining key vault access policy
  - Create virtual machine with OS disk encrypted using customer managed keys and one data disk, lun1 encrypted using
    platform-managed key
  - Deallocated vm, convert data disk lun1 encryption to customer-managed key, start vm
  - Create a new disk encrypted using customer-managed key
  - Attach the disk to the vm as lun2
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-java-create-encrypted-vms-using-customer-managed-key.git

    cd compute-java-create-encrypted-vms-using-customer-managed-key

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.