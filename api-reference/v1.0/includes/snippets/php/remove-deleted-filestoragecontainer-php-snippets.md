---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php
use Microsoft\Graph\GraphServiceClient;


$graphServiceClient = new GraphServiceClient($tokenRequestContext, $scopes);


$graphServiceClient->storage()->fileStorage()->deletedContainers()->byFileStorageContainerId('fileStorageContainer-id')->delete()->wait();

```