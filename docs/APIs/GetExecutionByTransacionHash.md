## GetExecutionByTransactionHash

Gets the block execution message by the transaction hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash    | string | The transaction hash |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0x75483c8aa17aea053e5307507934d2e9ab24216a3f74f82b32cbdf7e16b74e6f"},
    "method": "GetExecutionByTransactionHash"
}'
```

### Output

```json
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0x75483c8aa17aea053e5307507934d2e9ab24216a3f74f82b32cbdf7e16b74e6f"},
    "method": "GetExecutionByTransactionHash"
}'
```



