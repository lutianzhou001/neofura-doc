## GetAssetInfos

Gets all assets information

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Addresses |array in strings       |contract hashes of assets to query.       |


### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfos",
  "params": {"Addresses":["0xd2a4cff31913016155e38e474a2c06d08be276cf"]},
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
                "decimals": 8,
                "firsttransfertime": 1468595301000,
                "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "holders": 163,
                "ispopular": true,
                "symbol": "GAS",
                "tokenname": "GasToken",
                "totalsupply": "5201274859792915",
                "type": "NEP17"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

