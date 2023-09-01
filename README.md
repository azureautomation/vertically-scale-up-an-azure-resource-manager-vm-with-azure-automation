Vertically scale up an Azure Resource Manager VM with Azure Automation
======================================================================

<#            

This Azure Automation runbook can help you vertically scale up an Azure Resource Manager VM. This runbook can run from an Azure alert or by itself. This is intended to run only in Azure Automation service. An Azure Automation account with a Managed Identity is required.


**SYNOPSIS**
  Connects to Azure using Managed Identity and vertically scales the VM

**DESCRIPTION**
  This runbook connects to Azure and scales up the VM 

**REQUIRED**
  1. You have to create a managed identity for your automation account.

**PARAMETER WebhookData**
   Required 
   This is the data that is sent in the webhook that is triggered from the VM alert rules

**NOTES**
   AUTHOR: Chetan Kaur
   LAST EDIT: August 30, 2023

**RELEASE NOTES**

2023-08-30 : Updated runbook with Managed Identity authentication  

#>

      
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
