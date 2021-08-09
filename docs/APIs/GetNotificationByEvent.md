## GetNotificationByEvent

Gets notifications by the event name.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Event |string       |The event name       |
| Limit |int |The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNotificationByEvent",
  "params": {"Event": "Transfer","Limit":2},
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
                "Vmstate": "HALT",
                "_id": "60f7fe975a26ad67090d7b68",
                "blockhash": "0x614a807a3e545df0cb5c96d4d387e620e3e34d441f849b9a4033e0b4f906805d",
                "contract": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
                "eventname": "Transfer",
                "index": 0,
                "state": {
                    "type": "Array",
                    "value": [
                        {
                            "type": "Any",
                            "value": null
                        },
                        {
                            "type": "ByteString",
                            "value": "krOcd6pg8ptXwXPO2Rfxf9Mhpus="
                        },
                        {
                            "type": "Integer",
                            "value": "100000000"
                        }
                    ]
                },
                "timestamp": 1468595301000,
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000"
            },
            {
                "Vmstate": "HALT",
                "_id": "60f7fe975a26ad67090d7b69",
                "blockhash": "0x614a807a3e545df0cb5c96d4d387e620e3e34d441f849b9a4033e0b4f906805d",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "eventname": "Transfer",
                "index": 1,
                "state": {
                    "type": "Array",
                    "value": [
                        {
                            "type": "Any",
                            "value": null
                        },
                        {
                            "type": "ByteString",
                            "value": "krOcd6pg8ptXwXPO2Rfxf9Mhpus="
                        },
                        {
                            "type": "Integer",
                            "value": "3000000000000000"
                        }
                    ]
                },
                "timestamp": 1468595301000,
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000"
            }
        ],
        "totalCount": 490928
    },
    "error": null
}
```



