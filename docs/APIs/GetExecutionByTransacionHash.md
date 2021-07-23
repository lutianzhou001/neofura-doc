## GetExecutionByTransactionHash

Gets the execution message of a block by the transaction hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash    | string | The transaction hash |

### Example
```shell

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0x0000000000000000000000000000000000000000000000000000000000000000"},
    "method": "GetExecutionByTransactionHash"
}'
```

### Output

// TODO
