# Skills measured
- Design, implement, and manage hybrid networking (10–15%)
- Design and implement core networking infrastructure (20–25%)
- Design and implement routing (25–30%)
- Secure and monitor networks (15–20%)
- Design and implement Private access to Azure Services (10–15%)

# Notes 

## Design, implement, and manage hybrid networking (10–15%)

### Design, implement, and manage a site-to-site VPN connection
#### Design a site-to-site VPN connection for high availability
#### Select an appropriate virtual network (VNet) gateway SKU
#### Identify when to use policy-based VPN versus route-based VPN
#### Create and configure a local network gateway
#### Create and configure an IPsec/IKE policy
#### Create and configure a virtual network gateway
#### Diagnose and resolve virtual network gateway connectivity issues

### Design, implement, and manage a point-to-site VPN connection
#### Select an appropriate virtual network gateway SKU
#### Plan and configure RADIUS authentication
#### Plan and configure certificate-based authentication
#### Plan and configure OpenVPN authentication
#### Plan and configure Azure Active Directory (Azure AD) authentication
#### Implement a VPN client configuration file
#### Diagnose and resolve client-side and authentication issues

### Design, implement, and manage Azure ExpressRoute
#### Choose between provider and direct model (ExpressRoute Direct)
#### Design and implement Azure cross-region connectivity between multiple ExpressRoute locations
#### Select an appropriate ExpressRoute SKU and tier
#### Design and implement ExpressRoute Global Reach
#### Design and implement ExpressRoute FastPath
#### Choose between private peering only, Microsoft peering only, or both
#### Configure private peering
#### Configure Microsoft peering
#### Create and configure an ExpressRoute gateway
#### Connect a virtual network to an ExpressRoute circuit
#### Recommend a route advertisement configuration
#### Configure encryption over ExpressRoute
#### Implement Bidirectional Forwarding Detection
#### Diagnose and resolve ExpressRoute connection issues

## Design and implement core networking infrastructure (20–25%)

### Design and implement private IP addressing for VNets
#### Create a VNet
#### Plan and configure subnetting for services, including VNet gateways, private endpoints, firewalls, application gateways, and VNet-integrated platform services
#### Plan and configure subnet delegation
#### Plan and configure subnetting for Azure Route Server

### Design and implement name resolution
#### Design public DNS zones
#### Design private DNS zones
#### Design name resolution inside a VNet
#### Configure a public or private DNS zone
#### Link a private DNS zone to a VNet

### Design and implement cross-VNet connectivity
#### Design service chaining, including gateway transit
#### Design VPN connectivity between VNets
#### Implement VNet peering

### Design and implement an Azure Virtual WAN architecture
#### Design an Azure Virtual WAN architecture, including selecting types and services
#### Connect a VNet gateway to Azure Virtual WAN
#### Create a hub in Virtual WAN
#### Create a network virtual appliance (NVA) in a virtual hub
#### Configure virtual hub routing
#### Create a connection unit

### Design and implement routing (25–30%)

### Design, implement, and manage VNet routing
#### Design and implement user-defined routes (UDRs)
#### Associate a route table with a subnet
#### Configure forced tunneling
#### Diagnose and resolve routing issues
#### Design and implement Azure Route Server
#### Design and implement an Azure Load Balancer
#### Choose an Azure Load Balancer SKU (Basic versus Standard)
#### Choose between public and internal
#### Create and configure an Azure Load Balancer (including cross-region)
#### Implement a load balancing rule
#### Create and configure inbound NAT rules
#### Create explicit outbound rules for a load balancer

### Design and implement Azure Application Gateway
#### Recommend Azure Application Gateway deployment options
#### Choose between manual and autoscale
#### Create a back-end pool
#### Configure health probes
#### Configure listeners
#### Configure routing rules
#### Configure HTTP settings
#### Configure Transport Layer Security (TLS)
#### Configure rewrite sets

### Implement Azure Front Door
#### Choose an Azure Front Door SKU
#### Configure health probes, including customization of HTTP response codes
#### Configure SSL termination and end-to-end SSL encryption
#### Configure multisite listeners
#### Configure back-end targets
#### Configure routing rules, including redirection rules

### Implement an Azure Traffic Manager profile
#### Configure a routing method (mode)
#### Configure endpoints
#### Create HTTP settings

### Design and implement an Azure Virtual Network NAT
#### Choose when to use a Virtual Network NAT
#### Allocate public IP or public IP prefixes for a NAT gateway
#### Associate a Virtual Network NAT with a subnet

## Secure and monitor networks (15–20%)

### Design, implement, and manage an Azure Firewall deployment
#### Design an Azure Firewall deployment
#### Create and implement an Azure Firewall deployment

### Configure Azure Firewall rules
#### Create and implement Azure Firewall Manager policies
#### Create a secure hub by deploying Azure Firewall inside an Azure Virtual WAN hub
#### Integrate an Azure Virtual WAN hub with a third-party NVA

### Implement and manage network security groups (NSGs)
#### Create an NSG
#### Associate an NSG to a resource
#### Create an application security group (ASG)
#### Associate an ASG to a NIC
#### Create and configure NSG rules
#### Interpret NSG flow logs
#### Validate NSG flow rules
#### Verify IP flow

### Implement a Web Application Firewall (WAF) deployment
#### Configure detection or prevention mode
#### Configure rule sets for Azure Front Door, including Microsoft managed and user defined
#### Configure rule sets for Application Gateway, including Microsoft managed and user defined
#### Implement a WAF policy
#### Associate a WAF policy

### Monitor networks
#### Configure network health alerts and logging by using Azure Monitor
#### Create and configure a Connection Monitor instance
#### Configure and use Traffic Analytics
#### Configure NSG flow logs
#### Enable and configure diagnostic logging
#### Configure Azure Network Watcher

## Design and implement Private access to Azure Services (10–15%)

### Design and implement Azure Private Link service and Azure Private Endpoint
#### Create a Private Link service
#### Plan private endpoints
#### Create private endpoints
#### Configure access to private endpoints
#### Integrate Private Link with DNS
#### Integrate a Private Link service with on-premises clients

### Design and implement service endpoints
#### Create service endpoints
#### Configure service endpoint policies

### Configure service tags
#### Configure access to service endpoints

### Configure VNet integration for dedicated platform as a service (PaaS) services
#### Configure App Service for regional VNet integration
#### Configure Azure Kubernetes Service (AKS) for regional VNet integration
#### Configure clients to access App Service Environment
