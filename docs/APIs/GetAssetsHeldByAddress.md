## GetAssetHeldByAddress

 Gets asset holders with the user address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address    | string | The user's wallet address |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

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

