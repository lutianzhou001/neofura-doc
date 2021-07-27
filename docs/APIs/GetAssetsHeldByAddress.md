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
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetsHeldByAddress",
  "params": {"Address":"0xeba621d37ff117d9ce73c1579bf260aa779cb392"},
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
                "_id": "60f7fe975a26ad67090d7b6e",
                "address": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                "asset": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "balance": "995397252107740"
            },
            {
                "_id": "60f7fe975a26ad67090d7b6b",
                "address": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                "asset": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
                "balance": "15000000"
            }
        ],
        "totalCount": 2
    },
    "error": null
}
```



