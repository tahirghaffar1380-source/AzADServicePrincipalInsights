__AzADServicePrincipalInsights aka AzADSPI__

Insights on Microsoft Entra ID Service Principals )



# Conten
- [Features](#
- 
- [Data](
- 

- [ort
* JSON export
  * Ingest data from the JSON files talytics workspace custom table using data colle
* CSV export (wip)
  * AA
  * AppRoleAssigrme-pnt Group ID that should be qts.ps1 -ManagementGroupId @('mgId0', 'mgIport`  - Sw outsLimit` Threshold for the HTML output (table formatted) to prevent unresponsive browser issue due to limited client device performance. A recommendation will be shown to download the CSV instead of openingARM` - Limi
* `ThrottleLimitLocal` - Limit the parallelism oId4AzContext` - If needed set a specific Subscriptienriched data in Json forbersLimit` - Defines the limit of AAD Group members; For AAD Groups that have more members than the defined limit Group members will not be resolved (default : 500)
* `Ntions` - Switch to disable the processing of Azure resource tOut` - Switch to opt out sending statistics for usage analysis

nSecretExpiryMax` - Define maximum expiry period forefaultrtificateExpiryWarning` - Define warning period for Service Principal certificate expiry (default : 14 days)
* `Appli- Define maximum expiry period for Sport on Service Principals that have a role assigment within the scope of the data  collatntity User Assigned - associat
```
$pscredential review2.png)  
![previewJzAPICall) PowerShel- pt
   * Fix hardcoded ARM API Url ustions to process. The ARM e delted and therefore should not be proce
* 20231217
    * Fix for SP names that contain escapablel](https://aka.ms* Servic CSV files from being generated if false
    * Fix: `NoJsonExport` is now working and preventing JSON-us/aity Credentials
    * Rearrange JSON output for Managed Identity associated Azure Resources
* 20221007
    * New feature - Managed Identity User Assignnts collection
            * No (Azure Resource side) Policy assignments collection

    * Azre android pipeline yml
entity governance state validatio
    * Use AzAPICall PowerShell module version 2.0
* 20220630
    * __Breaking Change__ on the Azure side: Instead of __RoleManagement.Read.All__ we require __RoleManagement.Read.Directory__
* 20220622_1
    * Fix `/providers/Microsoft.Authorization/roleAssignmentSchedule
    * Use AzAPICall PowerShell module version 2.0
 ivileged Role Administrator, Privile
    * minor fixes
* 20220505_1
    * fix: `using:scriptPath` variable in foreach parallel (this is only relevant for Azure DevOps and GitHub if you have a non default folder structure in y
* 20220501_atHaveARoleAssignow that Management Grnor bug fixes
    * performance 
* 20220425_2

    * use AzAPICall module version 2.0
* 20220404_1 
    * a

Also check you to keep up with the pace by providing overview and insights on new as Azure Policy's Policy definitions, initiatives (Set definitions), aliases and Azure RBAC's Role definitions and resource provider operations.

# Azur20.png "example output")

Also check out th://aka.ms/AzGovViz). The tool is intended to help you to get a holiew on your technical Azure Governance implementation by connecting the dots.  
It is a PowerShell script that iterates your Azure Tenant's Management Group hierarchy tion level, it captures most relevant Azurerk/reference/t developed by a Microsoft employee, AzADServicePrincipalInsights is not a Microsoft servicect, there are none implicit or explicit obligations relate with
