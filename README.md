Introduction
* We are going to create a Static Public IP for Ingress in Azure AKS
* Associate that Public IP to Ingress Controller during installation.
* We are going to create a namespace ingress-basic for Ingress Controller where all ingress controller related things will be placed.
* we install cert-manager for SSL certificates also in same namespace.
* Caution Note: This namespace is for Ingress controller stuff, ingress resource we can create in any other namespaces and not an issue. Only condition is creating ingress resource and ingress pointed application in same namespace (Example: App1 and Ingress resource of App1 should be in same namespace)
* Implement SSL using Lets Encrypt
* Provide Access to DNZ Zones using Azure Managed Service Identity for External DNS pod to create Record Sets in Azure DNS Zones
* Create Manifest yml for all the resources
* Deploy a simple Nginx App1 and App2 with Ingress manifest
* We are going to implement Domain Name based routing using Ingress
* We are going to use 2 applications for this.

 ![alt text](https://github.com/mdsahmad/task3/blob/d89c959b387d2bcedaade0d3dabb143e0f98c442/IngressinAKS-SSL.png)
