## GetAssetInfosByName

Gets the asset information with the token name(fuzzy search supported).

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Name |string       |The token name.       |
| Standard |string       |The token standard of NEP11 or NEP17, which can be omitted. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfosByName",
  "params": {"Name":"GasTo","Standard":"NEP17"},
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
                "_id": "614bef0ea14111843551a7fd",
                "decimals": 8,
                "firsttransfertime": 1468595301000,
                "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "holders": 600,
                "ispopular": true,
                "symbol": "GAS",
                "tokenname": "GasToken",
                "totalsupply": "5220485458158932",
                "type": "NEP17"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```
