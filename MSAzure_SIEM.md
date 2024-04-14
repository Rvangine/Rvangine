<strong> Azure Cloud Infrastructure Setup and Virtual Machine Deployment </strong>

- Orchestrated the setup of an Azure tenant, establishing a robust subscription and tenant structure to facilitate cloud-based operations.
- Strategically created a Windows 10 Pro Virtual Machine and an Ubuntu Linux Virtual Machine within the EAST US 2 region, optimizing for cost-effective yet efficient configurations.
- Configured the Resource Group ("RG-Cyber-Lab") and Virtual Network ("Lab-VNet") to streamline resource management and network connectivity for both VM instances.
- Carefully tailored network security by implementing Network Security Groups (NSGs) for inbound traffic, deploying Layer 4 firewalls to allow comprehensive traffic management and ensure secure communication.
- Methodically documented the Azure subscription details, VM configurations, and network security settings for ongoing reference and management.

<strong> Windows Server Configuration and SQL Server Installation for Vulnerability Testing </strong>

- Configured a Windows-based Virtual Machine within an Azure environment for vulnerability testing and SQL Server deployment. 
- Disabled Windows Firewall to simulate an open environment for testing purposes. Installed SQL Server Evaluation, adopting default login credentials and SQL Server Management Studio (SSMS), enhancing database management capabilities.
- Enabled SQL logging for integration with Windows Event Viewer, ensuring comprehensive monitoring and diagnostic capabilities.
- Conducted connectivity tests by pinging and establishing SSH login to the Ubuntu-based Virtual Machine ("linux-vm"), validating cross-platform interaction within the cloud-based environment.

<strong> Log Analytics Workspace and Azure Sentinel Integration </strong>

- Created a Log Analytics Workspace named LAW-Cyber-Lab-0x, serving as the central log aggregator for data analysis and monitoring.
- Configured Azure Sentinel and established a connection with the Log Analytics Workspace for seamless data ingestion and analysis.
- Set up a geoip watchlist within Azure Sentinel, utilizing a local file as the data source containing approximately 27,000 records.
- Specified watchlist parameters including Name/Alias (geoip), Source type (Local File), and Search Key (network).
- Monitored the upload and synchronization process to ensure successful data transfer into the Log Analytics Workspace.
- Verified data integration by querying _GetWatchlist("geoip") within the Log Analytics Workspace, confirming proper data retrieval and utilization within Azure Sentinel for enhanced threat detection and cybersecurity monitoring.
