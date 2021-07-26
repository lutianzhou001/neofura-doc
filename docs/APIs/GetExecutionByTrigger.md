## GetExecutionByTrigger

Gets the execution message of a block by the trigger.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Trigger    | string | The trigger name |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Trigger":"System"},
    "method": "GetExecutionByTrigger"
}'
```

### Output

// TODO
