---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php
use Microsoft\Graph\Beta\GraphServiceClient;


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$graphServiceClient->security()->cases()->ediscoveryCases()->byEdiscoveryCaseId('ediscoveryCase-id')->legalHolds()->byEdiscoveryHoldPolicyId('ediscoveryHoldPolicy-id')->userSources()->byUserSourceId('userSource-id')->delete()->wait();

```