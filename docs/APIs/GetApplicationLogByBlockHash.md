## GetApplicationLogByBlockHash


Gets the applicationlog by blockhash

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The blockhash |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetApplicationLogByBlockHash",
  "params": {"BlockHash": "0x230678b1d66b103a6bcf886294fe4f0ddab8323dd79aea58e0438ecff51e9a6f" },
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
                "_id": "611b7d775052e9839723b9ea",
                "blockhash": "0x230678b1d66b103a6bcf886294fe4f0ddab8323dd79aea58e0438ecff51e9a6f",
                "exception": null,
                "gasconsumed": 0,
                "notifications": [
                    {
                        "Vmstate": "HALT",
                        "_id": "611b7d775052e9839723b9eb",
                        "blockhash": "0x230678b1d66b103a6bcf886294fe4f0ddab8323dd79aea58e0438ecff51e9a6f",
                        "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
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
                                    "value": "USCpDoINemxSJkNosYourc3rWM4="
                                },
                                {
                                    "type": "Integer",
                                    "value": "50000000"
                                }
                            ]
                        },
                        "timestamp": 1626797044275,
                        "txid": "0x0000000000000000000000000000000000000000000000000000000000000000"
                    }
                ],
                "timestamp": 1626797044275,
                "trigger": "OnPersist",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "vmstate": "HALT"
            },
            {
                "_id": "611b7d775052e9839723b9e9",
                "blockhash": "0x230678b1d66b103a6bcf886294fe4f0ddab8323dd79aea58e0438ecff51e9a6f",
                "exception": null,
                "gasconsumed": 0,
                "notifications": [
                    {
                        "Vmstate": "HALT",
                        "_id": "611b7d775052e9839723b9eb",
                        "blockhash": "0x230678b1d66b103a6bcf886294fe4f0ddab8323dd79aea58e0438ecff51e9a6f",
                        "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
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
                                    "value": "USCpDoINemxSJkNosYourc3rWM4="
                                },
                                {
                                    "type": "Integer",
                                    "value": "50000000"
                                }
                            ]
                        },
                        "timestamp": 1626797044275,
                        "txid": "0x0000000000000000000000000000000000000000000000000000000000000000"
                    }
                ],
                "timestamp": 1626797044275,
                "trigger": "PostPersist",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "vmstate": "HALT"
            }
        ],
        "totalCount": 2
    },
    "error": null
}
```
