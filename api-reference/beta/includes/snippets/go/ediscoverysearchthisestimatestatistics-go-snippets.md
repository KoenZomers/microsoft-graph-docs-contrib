---
description: "Automatically generated file. DO NOT MODIFY"
---

```go


// Code snippets are only available for the latest major version. Current major version is $v0.*

// Dependencies
import (
	  "context"
	  msgraphsdk "github.com/microsoftgraph/msgraph-beta-sdk-go"
	  graphsecurity "github.com/microsoftgraph/msgraph-beta-sdk-go/security"
	  graphmodelssecurity "github.com/microsoftgraph/msgraph-beta-sdk-go/models/security"
	  //other-imports
)

requestBody := graphsecurity.NewEstimateStatisticsPostRequestBody()
statisticsOptions := graphmodels.INCLUDEREFINERS, INCLUDEQUERYSTATS, INCLUDEUNINDEXEDSTATS, ADVANCEDINDEXING, LOCATIONSWITHOUTHITS_STATISTICSOPTIONS 
requestBody.SetStatisticsOptions(&statisticsOptions) 

// To initialize your graphClient, see https://learn.microsoft.com/en-us/graph/sdks/create-client?from=snippets&tabs=go
graphClient.Security().Cases().EdiscoveryCases().ByEdiscoveryCaseId("ediscoveryCase-id").Searches().ByEdiscoverySearchId("ediscoverySearch-id").MicrosoftGraphSecurityEstimateStatistics().Post(context.Background(), requestBody, nil)


```