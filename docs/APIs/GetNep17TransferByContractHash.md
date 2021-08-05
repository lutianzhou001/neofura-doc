## GetNep17TransferByContractHash

 Gets the nep17 transfer by the contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash. |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |itn |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep17TransferByAddress",
  "params": {"Address": "0xeba621d37ff117d9ce73c1579bf260aa779cb392","Limit":2},
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
                "_id": "60f7fead5a26ad67090d7dea",
                "blockhash": "0xc60ebf0e7610bc4844e297ea3b4216f07ddb526dcc84126c6f5a3ad74bfc8232",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                "frombalance": "2999999921996320",
                "timestamp": 1621309747336,
                "to": null,
                "tobalance": "0",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "value": "77989680",
                "vmstate": "HALT"
            },
            {
                "_id": "60f7feae5a26ad67090d7dfc",
                "blockhash": "0xc60ebf0e7610bc4844e297ea3b4216f07ddb526dcc84126c6f5a3ad74bfc8232",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                "frombalance": "2999999921996320",
                "netfee": 8145220,
                "sysfee": 69844460,
                "timestamp": 1621309747336,
                "to": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                "tobalance": "750002000",
                "txid": "0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68",
                "value": "2000",
                "vmstate": "HALT"
            }
        ],
        "totalCount": 48
    },
    "error": null
}
```



