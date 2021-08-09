## GetAssetInfosByName

Gets the asset information with the token name(fuzzy search supported).

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Name |string       |The token name.       |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfosByName",
  "params": {"Name":"GasTo"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "6103a4ef822699ec7ebc63f0",
                "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "holders": 163,
                "ispopular": true,
                "symbol": "GAS",
                "tokenname": "GasToken"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

