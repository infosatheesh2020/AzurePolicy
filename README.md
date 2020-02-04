# AzurePolicy
Azure Policy collection

## 01.App_Service_HttpsOnly_Remediate

  Remediates the webapp by adding httpsOnly falg to true if not enabled already

  - "displayName": "deployIfNotExists - Web Application should only be accessible over HTTPS",
  - "description": "Use of HTTPS ensures server/service authentication and protects data in transit from network layer eavesdropping attacks.",



## 02.Windows_VM_Diagnostics_Remediate

Remediates the VM by adding diagnostics setting to the storage account if not already

  - "displayName": "deployIfNotExists - Enable Diagnostics setting for Windows VM",
  - "description": "Enabling the disgnostic setting for the Windows VM and send those logs to the storage account.",
