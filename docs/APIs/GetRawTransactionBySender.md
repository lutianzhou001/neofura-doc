## GetRawTransactionBySender

 Gets the raw transaction by the sender's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Sender    | string | The sender's address |
| Limit     | int | The number of items to return. It is optional and used for paging. |
| Skip |itn |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Sender":"Nd29sK8Wnri8HAAW2vD2APFP8SJJEu3pS4"},
    "method": "GetRawTransactionBySender"
}'
```

### Output

// TODO

