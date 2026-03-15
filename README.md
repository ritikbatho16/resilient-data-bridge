# Resilient-data-bridge
Azure Secure 2-Tier Architecture

Implemented a secure 2-tier cloud architecture on Microsoft Azure using Virtual Networks, Network Security Groups, Bastion access, and Network Watcher for connectivity validation.

Project Title:
 
 ==Secure Two-Tier Cloud Architecture Deployment==

Platform:
 
 ==Microsoft Azure==


Description:

*Designed and deployed a secure two-tier architecture using Azure Virtual Network with segmented subnets for web and database layers.

*Implemented Network Security Groups (NSGs) to control traffic, allowing HTTP/HTTPS to the web layer and restricting SQL access to the database only from the web subnet.

*Configured Azure Bastion to enable secure VM access without assigning public IP addresses.

*Implemented outbound traffic restrictions on the database subnet to prevent data exfiltration.

*Enabled Service Endpoints for Microsoft.Storage to ensure secure connectivity through Azure backbone network.

*Performed network validation using Network Watcher tools such as IP Flow Verify and Connection Troubleshoot to confirm security policies and connectivity.


Key Skills Used:

=Azure Virtual Network

=Subnet Design

=Network Security Groups

=Azure Bastion

=Azure Network Watcher

=Cloud Security & Monitoring


Benefits:

-Improved security through network isolation

-Secure VM access using Bastion

-Controlled traffic using NSG rules

-Data exfiltration prevention

-Better monitoring using Network Watcher



