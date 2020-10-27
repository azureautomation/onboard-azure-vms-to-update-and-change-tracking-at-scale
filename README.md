Onboard Azure VMs to update and change tracking at scale
========================================================

            

This sample automation runbook onboards Azure VMs for either the Update or ChangeTracking (which includes Inventory) solution. It requires an existing Azure VM to already be onboarded to the solution as it uses this information to onboard the new VM to the
 same Log Analytics workspace and Automation Account. This Runbook needs to be run from the Automation account that you wish to connect the new VM to. It depends on the Enable-AutomationSolution runbook that is available from the gallery and https://github.com/azureautomation/runbooks/blob/master/Utility/ARM/Enable-AutomationSolution.ps1.
 If this Runbook is not present, it will be automatically imported.


 

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
