---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Trafficmanager
  platforms: java
---

# Getting Started with Trafficmanager - Manage Traffic Manager - in Java #


  Azure traffic manager sample for managing profiles.
   - Create a domain
   - Create a self-signed certificate for the domain
   - Create 5 app service plans in 5 different regions
   - Create 5 web apps under the each plan, bound to the domain and the certificate
   - Create a traffic manager in front of the web apps
   - Disable an endpoint
   - Delete an endpoint
   - Enable an endpoint
   - Change/configure traffic manager routing method
   - Disable traffic manager profile
   - Enable traffic manager profile
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/traffic-manager-java-manage-profiles.git

    cd traffic-manager-java-manage-profiles

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
