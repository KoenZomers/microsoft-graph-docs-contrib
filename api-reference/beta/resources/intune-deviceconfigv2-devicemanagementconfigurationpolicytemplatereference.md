---
title: "deviceManagementConfigurationPolicyTemplateReference resource type"
description: "Policy template reference information"
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: resourcePageType
ms.date: 08/01/2024
---

# deviceManagementConfigurationPolicyTemplateReference resource type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Policy template reference information

## Properties
|Property|Type|Description|
|:---|:---|:---|
|templateId|String|Template id|
|templateFamily|[deviceManagementConfigurationTemplateFamily](../resources/intune-deviceconfigv2-devicemanagementconfigurationtemplatefamily.md)|Template Family of the referenced Template. This property is read-only. Possible values are: `none`, `endpointSecurityAntivirus`, `endpointSecurityDiskEncryption`, `endpointSecurityFirewall`, `endpointSecurityEndpointDetectionAndResponse`, `endpointSecurityAttackSurfaceReduction`, `endpointSecurityAccountProtection`, `endpointSecurityApplicationControl`, `endpointSecurityEndpointPrivilegeManagement`, `enrollmentConfiguration`, `appQuietTime`, `baseline`, `unknownFutureValue`, `deviceConfigurationScripts`, `deviceConfigurationPolicies`, `windowsOsRecoveryPolicies`, `companyPortal`.|
|templateDisplayName|String|Template Display Name of the referenced template. This property is read-only.|
|templateDisplayVersion|String|Template Display Version of the referenced Template. This property is read-only.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.deviceManagementConfigurationPolicyTemplateReference"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.deviceManagementConfigurationPolicyTemplateReference",
  "templateId": "String",
  "templateFamily": "String",
  "templateDisplayName": "String",
  "templateDisplayVersion": "String"
}
```
