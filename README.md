# OMSDataInjection-PSModule

##Description
The OMSDataInjection PowerShell module provides abilities to inject custom data into Microsoft Operations Management Suite (OMS) using it's HTTP data injection API. This module also provides an Azure Automation / SMA connection type called 'OMSWorkspace', so it can be used in automation runbooks.

##Install Instruction
###Install from PowerShell Gallery
Install-module OMSDataInjection

###Manually Install
Download this module from github, and place the OMSDataInjection module folder to 'C:\Program Files\WindowsPowerShell\Modules'

###Download from PowerShell Gallery
Find-Module OMSDataInjection | Save-Module -Force -Path 'C:\Temp'

##PowerShell functions
###New-OMSDataInjection
Injecting custom data into Microsoft Operations Management Suite (OMS) Log Analytics using its HTTP Data Injection API.