# Azure Cloud Portfolio ☁️ My Azure Cloud Journey! Architecture Diagrams and Solutions

## Lab 01: VM with Outbound Internet Access for Updates
This architecture demonstrates an Azure Virtual Machine configured with a Standard Public IP to allow outbound access to the internet (specifically for downloading OS updates).

### Resources Used:
* **Virtual Network (VNet)**: Hub Network (10.0.0.0/16)
* **Subnet**: Operations Subnet (10.0.1.0/24)
* **Compute**: Azure VM (`VM1`)
* **Network**: Standard Public IP (`PIP-Web-01`) associated with the NIC to enable internet connectivity
* **Traffic Flow**: Outbound (VM -> NIC -> Public IP -> Internet)

### Architecture Diagram:
![Lab 01 Diagram](lab-01-architecture.png)


