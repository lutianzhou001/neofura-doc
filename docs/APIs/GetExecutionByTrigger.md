## GetExecutionByTrigger

Gets the execution message of a block by the trigger.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Trigger    | string | 触发       |
| Limit | int | Limit. It is optional. |
| Skip | int | Skip. It is optional. |

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
