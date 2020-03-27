---
title: Remove a webhook
---

# Remove a webhook

This example shows you how to remove a webhook

Replace the following placeholder value in the sample code:

| Key | Description |
| --- | ----------- |
| bearer_token      | Your OAuth token. [Read more about OAuth tokens](/concepts/guides/create-an-access-token) |
| id                | Unique identifier of the webhook |

``` bash
curl --location --request DELETE 'https://api.vonage.com/t/vbc.prod/vis/v1/self/webhooks/$id' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer $bearer_token'
```