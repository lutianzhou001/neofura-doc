## GetNotificationByEvent

Gets the Notification By the event.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Event |string       |The event name       |
| Limit |Int |Limit. It is optional |
| Skip |Int |Skip. It is optional |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNotificationByEvent",
  "params": {"Event": "Transfer" },
  "id": 1
}'
```

### Output

// TODO

