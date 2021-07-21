## GetAssetHeldByAddress

 Gets asset holders with the contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address    | string | The contract script hash. |
| Limit     | int      | Limit. It is optional. |
| Skip |int |Skip. It is optional. |

### Example


```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Address":"0x3555537a8d50d0a7738a42ae605f86708e73d0ac"},
    "method": "GetAssetsHeldByAddress"
}'
```

### Output

// TODO

