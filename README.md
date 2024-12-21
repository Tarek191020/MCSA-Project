# MCSA-Project
## Project Overview  
This project documents the configuration and deployment of a comprehensive Windows Server environment as part of an MCSA (Microsoft Certified Solutions Associate) training project. The setup includes primary and child domain controllers, a web server hosting secure and non-secure websites, DNS zones, and Group Policy management for user-specific configurations.

## Features and Configuration Details

### 1. Primary Domain Controller Setup  
- Configured the main server as the Primary Domain Controller (PDC) with the domain name `MCS.local`.  
- Installed and managed Active Directory Domain Services (AD DS).  

### 2. Child Domain Configuration  
- Set up a secondary server in Alexandria as a Child Domain Controller (CDC) with the domain name `alex.mcs.local`.  
- Established trust relationships and ensured domain replication.  

### 3. Web Server Deployment  
- Installed a Web Server hosting two websites:  
  - **Website 1:** Configured for HTTP access.  
  - **Website 2:** Secured with HTTPS using an SSL certificate.  
- Published websites with unique hostnames using DNS records.  

### 4. DNS Zones Configuration  
- Configured DNS zones on the primary server for hostname-to-IP mapping of hosted websites.  
- Managed `A` and `CNAME` records for domain resolution.  

### 5. Group Policy Configuration for User IT1 (Primary Domain)  
- Created user `IT1` and applied the following Group Policies:  
  - Restricted access to the Control Panel.  
  - Disabled USB access.  
  - Deployed a custom desktop background image.  

### 6. Group Policy Configuration for User HR1 (Child Domain)  
- Created user `HR1` and applied the following Group Policies:  
  - Deployed custom desktop background image `HR1`.  
  - Automatically installed shared software on `HR1`’s system.  

## Learning Objectives  
This project demonstrates practical skills in:  
- Configuring and managing Windows Server environments.  
- Setting up domain controllers and inter-domain structures.  
- Managing DNS zones for hosted services.  
- Deploying and securing web servers.  
- Implementing user-specific Group Policies for environment control and security.

## How to Use  
This repository serves as a reference for IT professionals and students seeking hands-on experience with Windows Server configurations. Each section includes configuration steps, scripts, and relevant documentation to replicate the setup.
