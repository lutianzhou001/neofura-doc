## GetTransferByBlockHeight

Gets the Nep11/Nep17 transfer by block hash.

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight | int | The blockheight |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |


### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetTransferByBlockHeight",
  "params": {"BlockHeight":38381,"Limit":2,"Skip":0},
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
                "_id": "6103d484896a7f59ab1c7093",
                "blockhash": "0x30412db167e56362bf58aa6056d5880a0a4e81b9d862127b50a5666c81d00420",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": null,
                "frombalance": "0",
                "timestamp": 1627384787720,
                "to": "0x112e406b22fd4efa9cf3eb33bf4bd8b44d18fe31",
                "tobalance": "155095885085",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "value": "50000000"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```
