## GetExecutionByTrigger

Gets the block execution message by the trigger name.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Trigger    | string | The trigger name |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetHoldersByContractHash",
  "params": {"ContractHash":"0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5","Limit":2},
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
                "_id": "60fa6976b75228de0a27aa03",
                "address": "0x6e528fc19e5c23cd0e2c7d2d864707f1737aca88",
                "asset": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
                "balance": "9999"
            },
            {
                "_id": "60f92c9cd674c9fe29c9fb46",
                "address": "0x053a90ecbba7eae1db3e441b0f010f5bbb5adb8c",
                "asset": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
                "balance": "9990"
            }
        ],
        "totalCount": 108
    },
    "error": null
}
```

