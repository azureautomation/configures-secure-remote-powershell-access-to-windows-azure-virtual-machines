Configures Secure Remote PowerShell Access to Windows Azure Virtual Machines
============================================================================

            

**Description:**


This script should be used in conjunction with the Windows Azure PowerShell cmdlets to enable secure Remote PowerShell connectivity to a virtual machine created in Windows Azure.


The script accepts the Subcription Name, the Windows Azure cloud service that hosts the virtual machine and the virtual machine name. It connects, retrieves the thumbprint for the certificate and downloads that specific certificate to the local machine.
 Once downloaded it installs the certificate into the local machines certificate store.


Note: To execute the script PowerShell must run elevated.


 


**Usage: **


 


 

 

 


        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
