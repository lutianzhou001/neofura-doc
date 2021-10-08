## GetNep17TransferByAddress

Gets all the transfers by the address (including from and to)

### Parameters

| Name | Type | Description |
| -------- | -------- | ------ |
| Address  | string | The user's address |
| Limit    | int | The number of items to return. It is optional and used for paging. |
| Skip     | int  | The number of items to skip. It is optional and used for paging. |
| ExcludeBonusAndBurn     | bool  | exclude transactions which to or from is null  |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep17TransferByAddress",
  "params": {"Address": "NbbBtdAbiCdvCaAhdT5dCgrZsAn1ZaUdot","ExcludeBonusAndBurn":true,"Limit":2},
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
                "_id": "614c43bfa1411184356c59af",
                "blockhash": "0x8a7fcdfd1227c2d425707605f010b0211dfb63670f6c998a4ca421197db6f0a0",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0xb31b1ef4b504f5413dbed7e6e58fd11dedb6f4ab",
                "frombalance": "821276368267",
                "netfee": 123262,
                "sysfee": 47662170,
                "timestamp": 1632388029414,
                "to": "0xd9e2093de3dc2ef7cf5704ceec46ab7fadd48e7f",
                "tobalance": "242600000005",
                "txid": "0x7c8663d61b247dbe822ac5b7c924204b3ac5a070c3e54ff9d3241ec24808e77c",
                "value": "2000000000",
                "vmstate": "HALT"
            },
            {
                "_id": "614c39ca3066938344847c14",
                "blockhash": "0xaf42456f93380c032bcb1b2efdde962d9c0eeb6e4fe2dda24d03f442b2ef1bc9",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0xb31b1ef4b504f5413dbed7e6e58fd11dedb6f4ab",
                "frombalance": "823588636617",
                "netfee": 1251030,
                "sysfee": 137341466,
                "timestamp": 1632302528857,
                "to": "0xd9e2093de3dc2ef7cf5704ceec46ab7fadd48e7f",
                "tobalance": "216000000000",
                "txid": "0x82f524bdcd9e3caf48873e28f181ee4cc042c0630a1cc784d7750b34a4a39a67",
                "value": "6000000000",
                "vmstate": "HALT"
            }
        ],
        "totalCount": 66
    },
    "error": null
}
```

