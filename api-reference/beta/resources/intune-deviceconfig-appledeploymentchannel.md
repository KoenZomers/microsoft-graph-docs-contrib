---
title: "appleDeploymentChannel enum type"
description: "Indicates the channel used to deploy the configuration profile. Available choices are DeviceChannel, UserChannel"
author: "jaiprakashmb"
ms.localizationpriority: medium
ms.subservice: "intune"
doc_type: enumPageType
ms.date: 08/01/2024
---

# appleDeploymentChannel enum type

Namespace: microsoft.graph

> **Important:** Microsoft Graph APIs under the /beta version are subject to change; production use is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

Indicates the channel used to deploy the configuration profile. Available choices are DeviceChannel, UserChannel

## Members
|Member|Value|Description|
|:---|:---|:---|
|deviceChannel|0|Send payload down over Device Channel.|
|userChannel|1|Send payload down over User Channel.|
|unknownFutureValue|2|Evolvable enumeration sentinel value. Do not use.|
