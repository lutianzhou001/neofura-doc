## GetBlockHeaderByBlockHash

Gets the block header by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetBlockInfoList",
  "params": {"Limit":10},
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
                "_id": "6103e545896a7f59ab1e790f",
                "hash": "0xc55e52421505155588635e9375b5462bfcba6652059ff20fd4fc62fd2f1b466f",
                "index": 53416,
                "size": 262059,
                "timestamp": 1627616329647,
                "transactioncount": 484
            },
            {
                "_id": "6103e3d8896a7f59ab1e5ca7",
                "hash": "0x16c01bc03d0bdfcb571f4bcf23371db5425ffdc80f399b2dcbedbd0269a0f0f4",
                "index": 53415,
                "size": 697,
                "timestamp": 1627616313734,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d8896a7f59ab1e5c9f",
                "hash": "0x828312dddb29c97ca609e69d420ad3e3ff3792a409891b5f22990a19e3a0b51d",
                "index": 53414,
                "size": 697,
                "timestamp": 1627616295710,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d8896a7f59ab1e5c97",
                "hash": "0x969eefd8092a99b47488cec461dde0cafd9fb98659c1259c41d8cb15b015666f",
                "index": 53413,
                "size": 697,
                "timestamp": 1627616279746,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d8896a7f59ab1e5c8f",
                "hash": "0x7edf6828c156294a28d810bc963ee30eba413fe6b58d45d5862620959fd423a7",
                "index": 53412,
                "size": 697,
                "timestamp": 1627616264677,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d8896a7f59ab1e5c87",
                "hash": "0x37efe5f0f237f1602bfe516cea24d3f72d01e63e903939703e2278ecdfb0e566",
                "index": 53411,
                "size": 697,
                "timestamp": 1627616249611,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d7896a7f59ab1e5c7f",
                "hash": "0x3f5bd93952bedcc9c80d462c0ea3579c5ca4298edea700e50f24aee62f86b7d4",
                "index": 53410,
                "size": 697,
                "timestamp": 1627616232870,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d7896a7f59ab1e5c77",
                "hash": "0xad959769663a4eff4f22c80e1d1ac52adf42b994130e498d7381d3507d48000a",
                "index": 53409,
                "size": 697,
                "timestamp": 1627616217816,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d7896a7f59ab1e5c6f",
                "hash": "0x6726fe4971c3e5d3378ece4b3438d1d74fcfea8e86ed90381c3879c2e8e642e1",
                "index": 53408,
                "size": 697,
                "timestamp": 1627616202754,
                "transactioncount": 0
            },
            {
                "_id": "6103e3d6896a7f59ab1e5c67",
                "hash": "0xf6dcf4d62f9464befc1bc88505a9ceaa4f3d39fe2f8bd20bf6e0062462b8cf9d",
                "index": 53407,
                "size": 697,
                "timestamp": 1627616187689,
                "transactioncount": 0
            }
        ],
        "totalCount": 53417
    },
    "error": null
}
```



