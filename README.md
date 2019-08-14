---
page_type: sample
languages:
- java
products:
- azure
services: Trafficmanager
platforms: java
author: yaohaizh
---

## Getting Started with Trafficmanager - Manage Traffic Manager - in Java ##


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

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/traffic-manager-java-manage-profiles.git

    cd traffic-manager-java-manage-profiles

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.