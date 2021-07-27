## GetAssetInfos

 Gets the all assets information

### Parameters

### Example

```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfos",
  "params": {"Limit":2},
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
                "_id": "60f7fe975a26ad67090d7b65",
                "decimals": 8,
                "firsttransfertime": 1468595301000,
                "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "ispopular": false,
                "symbol": "GAS",
                "tokenname": "GasToken",
                "totalsupply": "3028316521052563"
            },
            {
                "_id": "60f7fe975a26ad67090d7b66",
                "decimals": 0,
                "firsttransfertime": 1468595301000,
                "hash": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
                "ispopular": false,
                "symbol": "NEO",
                "tokenname": "NeoToken",
                "totalsupply": "100000000"
            }
        ],
        "totalCount": 190
    },
    "error": null
}
```

