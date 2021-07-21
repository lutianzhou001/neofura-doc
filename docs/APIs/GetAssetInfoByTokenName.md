## GetAssetInfoByTokenName

 Gets the asset information with the token name.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TokenName |string       |The token name.       |

### Output

// TODO

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfoByTokenName",
  "params": {"TokenName":"GasToken"},
  "id": 1
}'
```

