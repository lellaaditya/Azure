# Microsoft Learn Offical

1. Manage Azure identities and governance (15-20%)
1.1 Manage Azure AD objects 
Every user who needs access to Azure resources needs an Azure user account. A user account 
contains all the information needed to authenticate the user during the sign-on process. Once 
authenticated, Azure AD builds an access token to authorize the user and determine what resources 
they can access and what they can do with those resources.
1.1.2 Create users and groups 
• Add or delete users - Azure Active Directory | Microsoft Docs
• Create a basic group and add members - Azure Active Directory | Microsoft Docs
• Create a new user | Microsoft Docs
• New-AzureADUser (AzureAD) | Microsoft Docs
• New-AzureADGroup (AzureAD) | Microsoft Docs
• New-AzureADMSGroup (AzureAD) | Microsoft Docs
1.1.3 Create Administrative Units 
• Administrative units in Azure Active Directory - Microsoft Entra | Microsoft Docs
• Create or delete administrative units - Azure Active Directory - Microsoft Entra | Microsoft 
Docs
1.1.3 Manage user and group properties 
• Edit your group information - Azure Active Directory | Microsoft Docs
• Add or update user profile information - Azure AD | Microsoft Docs
• Bulk create users in the Azure Active Directory portal | Microsoft Docs
• Set-AzureADUser (AzureAD) | Microsoft Docs
• Set-AzureADGroup (AzureAD) | Microsoft Docs
• Set-AzureADMSGroup (AzureAD) | Microsoft Docs
1.1.4 Manage device settings 
• How to manage devices using the Azure portal | Microsoft Docs
1.1.5 Perform bulk user updates 
• Import data into my directory | Microsoft Docs
• Bulk upload to add or create members of a group - Azure Active Directory | Microsoft Docs
1.1.6 Manage guest accounts 
• What is B2B collaboration in Azure Active Directory? | Microsoft Docs
• Add B2B collaboration users in the Azure portal - Azure AD | Microsoft Docs
• Manage guest access with access reviews - Azure AD | Microsoft Docs
• Quickstart: Add guest users in the Azure portal - Azure AD | Microsoft Docs
1.1.7 Configure Azure AD Join 
• How to plan your Azure Active Directory join implementation | Microsoft Docs
• Plan hybrid Azure Active Directory join - Azure Active Directory | Microsoft Docs
• Configure hybrid Azure Active Directory join for managed domains | Microsoft Docs
1.1.8 Configure self-service password reset 
• Deployment considerations for Azure Active Directory self-service password reset | 
Microsoft Docs
• Self-service password reset deep-dive - Azure Active Directory | Microsoft Docs
• Customize self-service password reset - Azure Active Directory | Microsoft Docs
NOT: Azure AD Connect; PIM
1.2 Manage role-based access control (RBAC) 
Securing your Azure resources, such as virtual machines, websites, networks, and storage, is a critical 
function for any organization using the cloud. You want to ensure that your data and assets are 
protected, but still, grant your employees and partners the access they need to perform their jobs. 
Role-based access control (RBAC) is an authorization system in Azure that helps you manage who has 
access to Azure resources, what they can do with those resources, and where they have access.
1.2.1 Create a custom role 
• Azure custom roles - Azure RBAC | Microsoft Docs
• Tutorial: Create an Azure custom role with Azure PowerShell - Azure RBAC | Microsoft Docs
• Tutorial: Create an Azure custom role with Azure CLI - Azure RBAC | Microsoft Docs
• Create or update Azure custom roles using Azure PowerShell - Azure RBAC | Microsoft Docs
• AZ-104 Study Guide: Microsoft Azure Administrator (vladtalkstech.com)
1.2.2 Provide access to Azure resources by assigning roles at different scopes 
• Add or remove Azure role assignments using the Azure portal - Azure RBAC | Microsoft Docs
• Add or change Azure subscription administrators | Microsoft Docs
• Classic subscription administrator roles, Azure roles, and Azure AD roles | Microsoft Docs
• Elevate access to manage all Azure subscriptions and management groups | Microsoft Docs
• Tutorial: Grant group access to Azure resources using Azure PowerShell - Azure RBAC | 
Microsoft Docs
• What is Azure role-based access control (Azure RBAC)? | Microsoft Docs
• Azure built-in roles - Azure RBAC | Microsoft Docs
1.2.3 Interpret access assignments 
• List Azure role assignments using the Azure portal - Azure RBAC | Microsoft Docs
• Understand Azure deny assignments - Azure RBAC | Microsoft Docs
1.3 Manage subscriptions and governance 
Managing resources across single or several subscriptions is a challenge. In this section, you’ll learn 
to manage your Azure subscriptions with the services provided.
1.3.1 Configure Azure policies 
• Overview of Azure Policy - Azure Policy | Microsoft Docs
• Azure Subscription Governance – Controlling resources with Tags, Policies, and Locks | 
Microsoft Docs
• Tutorial: Build policies to enforce compliance - Azure Policy | Microsoft Docs
• Quickstart: New policy assignment with the portal - Azure Policy | Microsoft Docs
• Quickstart: New policy assignment with PowerShell - Azure Policy | Microsoft Docs
• Quickstart: New policy assignment with Azure CLI - Azure Policy | Microsoft Docs
1.3.2 Configure resource locks 
• Lock resources to prevent changes - Azure Resource Manager | Microsoft Docs
1.3.3 Apply and manage tags on resources 
• Tag resources, resource groups, and subscriptions for a logical organization - Azure Resource 
Manager | Microsoft Docs
• Tutorial: Manage tag governance - Azure Policy | Microsoft Docs
1.3.4 Manage resource groups 
• Manage resource groups - Azure portal - Azure Resource Manager | Microsoft Docs
• Manage resources - Azure PowerShell - Azure Resource Manager | Microsoft Docs
• Manage resources - Azure CLI - Azure Resource Manager | Microsoft Docs
1.3.7 Manage subscriptions 
• Add or change Azure subscription administrators | Microsoft Docs
• Create an additional Azure subscription | Microsoft Docs
• Export your Azure subscription top-level information | Microsoft Docs
1.3.8 Manage Costs 
• Overview of Azure Cost Management + Billing | Microsoft Docs
• Optimize your cloud investment with Azure Cost Management | Microsoft Docs
• Quickstart - Explore Azure costs with cost analysis | Microsoft Docs
1.3.9 Configure management groups 
• Organize your resources with management groups - Azure Governance - Azure governance | 
Microsoft Docs
• Quickstart: Create a management group with the portal - Azure governance | Microsoft Docs
2. Implement and manage storage (10-15%)
2.1 Manage storage accounts 
An Azure storage account contains all of your Azure Storage data objects: blobs, files, queues, tables, 
and disks. The storage account provides a unique namespace for your Azure Storage data that is 
accessible from anywhere in the world over HTTP or HTTPS. Data in your Azure storage account is 
durable and highly available, secure, and massively scalable.
2.1.1 Configure network access to storage accounts 
• Manage account access keys - Azure Storage | Microsoft Docs
• Configure Azure Storage firewalls and virtual networks | Microsoft Docs
2.1.2 Create and configure storage accounts 
• Storage account overview - Azure Storage | Microsoft Docs
• Create a storage account - Azure Storage | Microsoft Docs
2.1.3 Generate shared access signature 
• Getting Started with Shared Access Signatures (SAS) - Code Samples | Microsoft Docs
• Delegate access with a shared access signature - Azure Storage | Microsoft Docs
• Grant limited access to data with shared access signatures (SAS) - Azure Storage | Microsoft 
Docs
2.1.4 Manage access keys 
• Manage account access keys - Azure Storage | Microsoft Docs
• Manage storage account keys with Azure Key Vault and the Azure CLI | Microsoft Docs
2.1.5 Implement Azure storage replication 
• Data redundancy - Azure Storage | Microsoft Docs
• Change how a storage account is replicated - Azure Storage | Microsoft Docs
2.1.6 Configure Azure AD Authentication for a storage account 
• Authorize access to blobs and queues using Active Directory - Azure Storage | Microsoft Docs
2.2 Manage data in Azure Storage 
Most organizations have diverse requirements for their cloud-hosted data. For example, storing data 
in a specific region, or needing separate billing for different data categories. Azure storage accounts 
let you formalize these types of policies and apply them to your Azure data.
2.2.1 Export from Azure job 
• Using Azure Import/Export to transfer data to and from Azure Storage | Microsoft Docs
• Create an export Job for Azure Import/Export | Microsoft Docs
2.2.2 Import into Azure job 
• Create an Import Job for Azure Import/Export | Microsoft Docs
2.2.3 Install and use Azure Storage Explorer 
• Introduction to Microsoft Azure Storage Explorer
• Get started with Storage Explorer | Microsoft Docs
• Quickstart - Create a blob with Azure Storage Explorer - Azure Storage | Microsoft Docs
2.2.4 Copy data by using AZCopy 
• Transfer data to or from Azure Files by using AzCopy v10 | Microsoft Docs
• Copy or move data to Azure Storage by using AzCopy v10 | Microsoft Docs
2.2.5 Implement Azure Storage replication 
• Configure object replication - Azure Storage | Microsoft Docs
• Change how a storage account is replicated - Azure Storage | Microsoft Docs
• Data redundancy - Azure Storage | Microsoft Docs
2.2.6 Configure blob object replication 
• Configure object replication - Azure Storage | Microsoft Docs
• Object replication overview - Azure Storage | Microsoft Docs
2.3 Configure Azure files and Azure blob storage 
Azure Files offers fully managed file shares in the cloud that are accessible via the industry standard 
Server Message Block (SMB) protocol or Network File System (NFS) protocol. Azure file shares can be 
mounted concurrently by cloud or on-premises deployments. Azure Files SMB file shares are 
accessible from Windows, Linux, and macOS clients. Azure Files NFS file shares are accessible from 
Linux or macOS clients. Additionally, Azure Files SMB file shares can be cached on Windows Servers 
with Azure File Sync for fast access near where the data is being used.
Azure Blob storage is Microsoft's object storage solution for the cloud. Blob storage is optimized for 
storing massive amounts of unstructured data. Unstructured data is data that doesn't adhere to a 
particular data model or definition, such as text or binary data.
2.3.1 Create an Azure file share 
• Create an Azure file share - Azure Files | Microsoft Docs
• Managing Azure file shares using Azure Storage Explorer | Microsoft Docs
• Create and use an Azure Files share on Windows VMs | Microsoft Docs
• Quickstart for managing Azure file shares with Azure portal | Microsoft Docs
• Quickstart for managing Azure file shares with Azure PowerShell | Microsoft Docs
• Quickstart for managing Azure file shares using the Azure CLI | Microsoft Docs
2.3.2 Create and configure Azure File Sync service 
• Deploy Azure File Sync | Microsoft Docs
• Planning for an Azure File Sync deployment | Microsoft Docs
• Tutorial - Extend Windows file servers with Azure File Sync | Microsoft Docs
2.3.3 Configure Azure blob storage 
• Introduction to Blob (object) storage - Azure Storage | Microsoft Docs
• Quickstart - Create a blob with the Azure portal - Azure Storage | Microsoft Docs
• Manage Azure Blob Storage resources with Storage Explorer | Microsoft Docs
2.3.4 Configure storage tiers for Azure blobs 
• Access tiers for Azure Blob Storage - hot, cool, and archive | Microsoft Docs
2.3.4 Configure blob lifecycle management 
• Optimize costs by automating Azure Blob Storage access tiers | Microsoft Docs
3. Deploy and manage Azure compute resources (25-30%)
3.1. Automate deployment of virtual machines (VMs) by using Azure Resource 
Manager templates 
To create and manage Azure virtual machines (VMs) in a consistent manner at scale, some form of 
automation is typically desired. There are many tools and solutions that allow you to automate the 
complete Azure infrastructure deployment and management lifecycle.
3.1.2 Modify Azure Resource Manager (ARM) template 
• Deploy resources with Azure portal - Azure Resource Manager | Microsoft Docs
• Update a resource in an Azure Resource Manager template - Azure Architecture Center | 
Microsoft Docs
• Template structure and syntax - Azure Resource Manager | Microsoft Docs
• Deploy template - Azure portal - Azure Resource Manager | Microsoft Docs
3.1.3 Configure a virtual hard disk (VHD) template 
• Create a Windows VM from a specialized VHD in the Azure portal - Azure Virtual Machines | 
Microsoft Docs
3.1.4 Deploy from template 
• Create a Windows VM from a template in Azure - Azure Virtual Machines | Microsoft Docs
• Deploy template - Azure portal - Azure Resource Manager | Microsoft Docs
• Deploy a Windows Virtual Machine with Azure Resource Manager Templates and PowerShell 
(microsoft.com)
3.1.5 Save a deployment as an ARM template 
• Download the template for an Azure VM - Azure Virtual Machines | Microsoft Docs
3.1.6 Deploy virtual machine extensions 
• Azure Custom Script Extension for Windows - Azure Virtual Machines | Microsoft Docs
• Run Custom Script Extension on Linux VMs in Azure - Azure Virtual Machines | Microsoft 
Docs
3.2 Configure VMs 
Azure virtual machines (VMs) can be created and configured through the Azure portal. This method 
provides a browser-based user interface to create VMs and their associated resources.
3.2.1 Configure Azure Disk Encryption 
• Enable Azure Disk Encryption for Linux VMs - Azure Virtual Machines | Microsoft Docs
• Enable Azure Disk Encryption for Windows VMs - Azure Virtual Machines | Microsoft Docs
3.2.2 Move VMs from one resource group to another 
• Move resources to a new subscription or resource group - Azure Resource Manager | 
Microsoft Docs
• Move a Windows VM resource in Azure - Azure Virtual Machines | Microsoft Docs
• Resize virtual machines | Blog y actualizaciones de Azure | Microsoft Azure
3.2.3 Manage VM sizes 
• Resize a Windows VM in Azure - Azure Virtual Machines | Microsoft Docs
• VM sizes - Azure Virtual Machines | Microsoft Docs
3.2.4 Add data discs 
• Attach a data disk to a Windows VM in Azure by using PowerShell - Azure Virtual Machines | 
Microsoft Docs
• Add a data disk to Linux VM using the Azure CLI - Azure Virtual Machines | Microsoft Docs
• Attach a data disk to a Linux VM - Azure Virtual Machines | Microsoft Docs
• Attach a managed data disk to a Windows VM - Azure - Azure Virtual Machines | Microsoft 
Docs
3.2.5 Configure networking 
• Create a virtual network - quickstart - Azure portal - Azure Virtual Network | Microsoft Docs
• Open ports to a VM using the Azure portal - Azure Virtual Machines | Microsoft Docs
3.2.6 Redeploy VMs 
• Redeploy Windows virtual machines in Azure - Azure Virtual Machines | Microsoft Docs
• Redeploy Linux Virtual Machines in Azure - Azure Virtual Machines | Microsoft Docs
• Redeploy a VM in a lab in Azure DevTest Labs - Azure DevTest Labs | Microsoft Docs
3.2.7 Configure high availability 
• Availability options for Azure Virtual Machines - Azure Virtual Machines | Microsoft Docs
3.2.8 Deploy and configure virtual machine scale sets 
• Azure virtual machine scale sets overview - Azure Virtual Machine Scale Sets | Microsoft 
Docs
3.3 Create and configure containers 
Azure Container Instances is a solution for any scenario that can operate in isolated containers, 
without orchestration. Run event-driven applications, quickly deploy from your container 
development pipelines, and run data processing and build jobs.
3.3.1 Configure sizing and scaling for Azure Container Instances 
• Serverless containers in Azure - Azure Container Instances | Microsoft Docs
• Quickstart - Deploy Docker container to container instance - Portal - Azure Container 
Instances | Microsoft Docs
• Quickstart - Deploy Docker container to container instance - Azure CLI - Azure Container 
Instances | Microsoft Docs
3.3.2 Configure container groups for Azure Container Instances 
• Introduction to container groups - Azure Container Instances | Microsoft Docs
3.3.3 Configure storage for Azure Kubernetes Service (AKS) 
• Concepts - Storage in Azure Kubernetes Services (AKS) - Azure Kubernetes Service | 
Microsoft Docs
3.3.4 Configure scaling for AKS 
• Scale an Azure Kubernetes Service (AKS) cluster - Azure Kubernetes Service | Microsoft Docs
3.3.5 Configure network connections for AKS 
• Concepts - Networking in Azure Kubernetes Services (AKS) - Azure Kubernetes Service | 
Microsoft Docs
3.3.6 Upgrade an AKS cluster 
• Upgrade an Azure Kubernetes Service (AKS) cluster - Azure Kubernetes Service | Microsoft 
Docs
3.4 Create and configure Azure App Service 
• App Service plans - Azure App Service | Microsoft Docs
3.4.1 Create an App Service plan 
• Manage App Service plan - Azure App Service | Microsoft Docs
3.4.2 Configure scaling settings in an App Service plan 
• Manage App Service plan - Azure App Service | Microsoft Docs
3.4.3 Create an App Service 
• Overview - Azure App Service | Microsoft Docs
• Quickstart: Deploy an ASP.NET web app - Azure App Service | Microsoft Docs
3.4.4 Secure an App Service 
• Security - Azure App Service | Microsoft Docs
3.4.5 Configure custom domain names 
Tutorial: Map existing custom DNS name - Azure App Service | Microsoft Docs
3.4.6 Configure backup for an App Service 
Back up an app - Azure App Service | Microsoft Docs
3.4.7 Configure networking settings 
Integrate your app with an Azure virtual network - Azure App Service | Microsoft Docs
3.4.8 Configure deployment settings 
• Deployment best practices - Azure App Service | Microsoft Docs
 
4. Configure and manage virtual networking (30-35%)
4.1 Implement and manage virtual networking 
Azure virtual networks enable Azure resources, such as virtual machines, web apps, and databases, 
to communicate with: each other, users on the Internet, and on-premises client computers. You can 
think of an Azure network as a set of resources that links other Azure resources.
4.1.1 Create and configure virtual networks, including peering 
• Azure Virtual Network | Microsoft Docs
• Quickstart: Create a virtual network - Azure portal - Azure Virtual Network | Microsoft Docs
• Azure Virtual Network peering | Microsoft Docs
• Connect virtual networks with VNet peering - tutorial - Azure portal | Microsoft Docs
• Create an Azure virtual network peering - different deployment models - same subscription | 
Microsoft Docs
• Create, change, or delete an Azure virtual network peering | Microsoft Docs
4.1.2 Configure private and public IP addresses 
• Create, change, or delete an Azure public IP address - Azure Virtual Network | Microsoft Docs
• Configure IP addresses for an Azure network interface | Microsoft Docs
4.1.3 Configure user-defined network routes 
• Azure virtual network traffic routing | Microsoft Docs 
4.1.4 Configure endpoints on subnets 
• Azure virtual network service endpoints | Microsoft Docs
• Azure virtual network service endpoint policies | Microsoft Docs
4.1.5 Implement subnets 
• Add, change, or delete an Azure virtual network subnet | Microsoft Docs
• Subnet extension in Azure | Microsoft Docs
4.1.3 Configure Azure DNS, including custom DNS settings and private or public DNS 
zones 
• Azure DNS documentation | Microsoft Docs
• Quickstart: Create a DNS zone and record - Azure portal - Azure DNS | Microsoft Docs
• Quickstart: Create an Azure DNS zone and record - Azure PowerShell - Azure DNS | Microsoft 
Docs
• Quickstart: Create an Azure DNS zone and record - Azure CLI - Azure DNS | Microsoft Docs
• Integrate Azure DNS with your Azure resources - Azure DNS | Microsoft Docs
• Tutorial: Map existing custom DNS name - Azure App Service | Microsoft Docs
• Quickstart - Create an Azure private DNS zone using Azure PowerShell | Microsoft Docs
• What is Azure Private DNS? | Microsoft Docs
• Tutorial: Host your domain and subdomain - Azure DNS | Microsoft Docs
4.2 Secure access to virtual networks 
4.2.1 Create security rules 
• Azure network security groups overview | Microsoft Docs
• Create, change, or delete an Azure network security group | Microsoft Docs
4.2.2 Associate a network security group (NSG) to a subnet or network interface 
• Create, change, or delete an Azure network security group | Microsoft Docs
4.2.3 Evaluate effective security rules 
• Microsoft Azure Network Security Group effective security rules evaluation - Daniel's Tech 
Blog
• Create, change, or delete an Azure network security group | Microsoft Docs
4.2.4 Deploy and configure Azure Firewall 
• Tutorial: Deploy & configure Azure Firewall using the Azure portal | Microsoft Docs
• Tutorial: Deploy and configure Azure Firewall in a hybrid network using the Azure portal | 
Microsoft Docs
• Deploy and configure Azure Firewall using Azure PowerShell | Microsoft Docs
• Deploy & configure Azure Firewall in hybrid network using PowerShell | Microsoft Docs
4.2.5 Deploy and configure Azure Bastion 
• Tutorial: Create an Azure Bastion host: Windows VM: portal | Microsoft Docs
• Create a Bastion host using Azure PowerShell | Microsoft Docs
4.3 Configure load balancing 
Load balancing provides a higher level of availability and scale by spreading incoming requests across 
multiple virtual machines.
4.3.1 Configure Application Gateway 
• Azure Application Gateway configuration overview | Microsoft Docs
• Frequently asked questions about Azure Application Gateway | Microsoft Docs
• Quickstart: Direct web traffic using the portal - Azure Application Gateway | Microsoft Docs
• Configure an internal load balancer (ILB) endpoint - Azure Application Gateway | Microsoft 
Docs
• Tutorial: Create using portal - Web Application Firewall | Microsoft Docs
4.3.2 Configure an internal or public load balancer 
• Internal Load Balancing | Azure blog and updates | Microsoft Azure
• Quickstart: Create an internal load balancer - Azure portal - Azure Load Balancer | Microsoft 
Docs
• Quickstart: Create an internal load balancer - Azure PowerShell - Azure Load Balancer | 
Microsoft Docs
• Quickstart: Create an internal load balancer - Azure CLI - Azure Load Balancer | Microsoft 
Docs
• Quickstart: Create an internal load balancer by using a template | Microsoft Docs
• Quickstart: Create a public load balancer - Azure template - Azure Load Balancer | Microsoft 
Docs
• Quickstart: Create a public load balancer - Azure portal - Azure Load Balancer | Microsoft 
Docs
• Quickstart: Create a public load balancer - Azure CLI - Azure Load Balancer | Microsoft Docs
• Quickstart: Create a public load balancer - Azure PowerShell - Azure Load Balancer | 
Microsoft Docs
4.3.3 Troubleshoot load balancing 
• Troubleshoot Azure Load Balancer | Microsoft Docs
• Diagnostics with metrics, alerts, and resource health - Azure Standard Load Balancer | 
Microsoft Docs
4.4 Monitor and troubleshoot virtual networking 
You can create complex and flexible setups in Azure that connect many virtual machines (VMs) to 
meet your needs. Just like in an on-premises network, configuration errors can result in problems 
that are challenging to troubleshoot. When you have to diagnose network problems in Azure, use 
Azure Network Watcher.
4.4.1 Monitor on-premises connectivity 
• Diagnose On-Premises connectivity via VPN gateway - Azure Network Watcher | Microsoft 
Docs
• Connect an on-premises network to Azure - Azure Architecture Center | Microsoft Docs
4.4.2 Configure and use Azure Monitor for Networks 
• ..
4.4.3 Use Azure Network Watcher 
• Azure Network Watcher | Microsoft Docs
• Introduction to resource troubleshooting - Azure Network Watcher | Microsoft Docs
• Troubleshoot VNET Gateway and Connections - Azure REST API - Azure Network Watcher | 
Microsoft Docs
4.4.4 Troubleshoot external networking 
• Troubleshoot Azure VNet gateway and connections - Azure PowerShell - Azure Network 
Watcher | Microsoft Docs
4.4.5 Troubleshoot virtual network connectivity 
• Troubleshoot virtual network peering issues | Microsoft Docs
• Troubleshooting connectivity problems between Azure VMs | Microsoft Docs
• Troubleshoot VNET Gateway and Connections - Azure REST API - Azure Network Watcher | 
Microsoft Docs
4.5.6 Integrate an on-premises network with an Azure virtual network 
A cross-premises Azure virtual network is connected to your on-premises network, extending your 
network to include subnets and virtual machines hosted in Azure infrastructure services. This 
connection lets computers on your on-premises network to directly access virtual machines in Azure 
and vice versa.
4.5.1. Create and configure Azure VPN Gateway 
• Tutorial - Create and manage a VPN Gateway: Azure portal | Microsoft Docs
• Azure VPN Gateway: configuration settings | Microsoft Docs
• Tutorial - Create and manage a VPN Gateway: Azure portal | Microsoft Docs
• Create a route-based Azure VPN Gateway: CLI | Microsoft Docs
• Azure VPN Gateway: Create route-based gateway: PowerShell | Microsoft Docs
4.5.2 Configure ExpressRoute 
• Extend an on-premises network using ExpressRoute - Azure Architecture Center | Microsoft 
Docs
4.5.3 Configure Azure Virtual WAN 
• Azure Virtual WAN Overview | Microsoft Docs
• Tutorial: Use Azure Virtual WAN to Create Site-to-Site connections | Microsoft Docs

