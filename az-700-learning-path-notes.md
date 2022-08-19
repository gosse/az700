# AZ-700 Designing and Implementing Microsoft Azure Networking Solutions Learning Path Notes

- [AZ-700 Designing and Implementing Microsoft Azure Networking Solutions
](https://docs.microsoft.com/en-us/learn/paths/design-implement-microsoft-azure-networking-solutions-az-700/)


## Azure Virtual Networks

### Introduction

- VNets are basic building block of Azure networks 
- Can peer non-overlapping IP VNets
- Communication with Internet is enabled by default
- Not just VMs can go in VNets - also Azure resources, app services, AKS, Azure SQL, storage accounts
- Can be connected to on-premises
- Network traffic can be filtered between subnets using NSGs, NVAs, and NAT 
- Network traffic can be routed and the default Azure routing table can be overridden 
- You can use any RFC1918 private IP space, divided how you want 
- You cannot use multicast, broadcast, loopback, link-local or the MS Magic DNS IP (168.63.129.16/32)
- You cannot add address space after creating the VNet 
- 5 IPs are reserved in each subnet - 
  - +0 network address
  - +1 gateway
  - +2, +3 map Azure DNS IPs to VNet space
  - +last broadcast
- Smallest supported subnet is /29, largest is /2 
- IPv6 subnets must be /64 
- Some Azure services require their own subnets 
- Subnets are smallest unit for IP addressing but NSGs can be used for further traffic filtering within a subnet (applied to NIC object)
- Availability Zones are unique physical locations within a region with independent power, cooling, and networking
  - Zonal services - resources can be pinned to specific AZ, e.g., VMs, disks, standard IPs 
  - Zone-redundant services - Resources distributed across AZs automatically (three+)
  - Non-regional services - Services always available from multiple Azure geographies resilient to zone-wide and region-wide outages

### Configure public IP services
- Public IP in Azure is dedicated to a resource until it's unassigned 
- Resources without Public IPs can communicate to the internet via NAT
- Two types, 
  - Dynamic - can change over the lifespan of the resources
  - Static - assigned address that will not change
- Two SKUs, 
  - Basic - static or dynamic, have a flow idle timeout of 4-30 minutes, default of 4
    - Open by default, NSG recommended 
    - Do not support availability zone scenarios (wut?)
  - Standard - always use static allocation, have a flow idle timeout of 4-30 minutes, default of 4
    - By default closed to inbound traffic, allow it in using an NSG 
    - Can be assigned to network interfaces, load balancers, application gateways, VPN gateways
    - Zone-redundant by default and optionally zonal 



## Design & Implement Hybrid Networking

## Design & Implement Azure ExpressRoute

## Load Balance non-HTTP(S) Traffic

## Load Balance HTTPS Traffic

## Design & Implement Private Access to Azure Services

## Design & Implement Network Monitoring