## GetBlockByBlockHash

 Gets the corresponding block information by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The block hash |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHash":"0xaa15bf961c577a9ee9a62774d12d74c6978a03ac782508f93f24aeee452387ff"},
    "method": "GetBlockByBlockHash"
}'
```

### Output

// TODO
