---
description: "Automatically generated file. DO NOT MODIFY"
---

```powershell

Import-Module Microsoft.Graph.Beta.DeviceManagement.Administration

$params = @{
	"@odata.type" = "#microsoft.graph.cloudPcUserSetting"
	displayName = "Example"
	selfServiceEnabled = $false
	localAdminEnabled = $true
	crossRegionDisasterRecoverySetting = @{
		crossRegionDisasterRecoveryEnabled = $false
		maintainCrossRegionRestorePointEnabled = $true
		disasterRecoveryNetworkSetting = @{
			regionName = "westus"
			regionGroup = "usEast"
		}
		disasterRecoveryType = "premium"
		userInitiatedDisasterRecoveryAllowed = $true
	}
	restorePointSetting = @{
		frequencyInHours = 16
		frequencyType = "sixteenHours"
		userRestoreEnabled = $true
	}
}

New-MgBetaDeviceManagementVirtualEndpointUserSetting -BodyParameter $params

```