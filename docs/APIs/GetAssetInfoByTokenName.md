## GetAssetInfoByTokenName

Gets the asset information with the token name.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TokenName |string       |The token name.       |

### Example

```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfoByTokenName",
  "params": {"TokenName":"GasToken"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fe975a26ad67090d7b65",
        "decimals": 8,
        "firsttransfertime": 1468595301000,
        "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "symbol": "GAS",
        "tokenname": "GasToken",
        "totalsupply": "3028316521052563"
    },
    "error": null
}
```

