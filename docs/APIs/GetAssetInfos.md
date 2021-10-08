## GetAssetInfos

Gets all assets information

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Addresses |array in strings       |contract hashes of assets to query.   |
| Standard | string | token standard in NEP17 and NEP11, which can be omitted.  |


### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfos",
  "params": {"Addresses":["0xd2a4cff31913016155e38e474a2c06d08be276cf"],"Standard":"NEP17"},
  "id": 1,
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
                "totalsupply": "5220483758158932",
                "type": "NEP17"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

