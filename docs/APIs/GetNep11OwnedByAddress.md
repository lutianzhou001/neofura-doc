## GetNep11OwnedByAddress

Gets the Nep11(NFT) related transaction information occurred at the given address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address    | string | The user's address |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","Limit":2},
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
                "_id": "60f8dc36831c6c19483c1f05",
                "blockhash": "0x9b8f20f6de65f2b287a2ac19137779887a3417973dc3de6ca658d5516220e249",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977154819,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "1",
                "tokenId": "R0hPU1RLW4OfMvf288O5NrolQ8Sj1Lqfee3XwITC3zVsdgImUA==",
                "txid": "0x502602766c35dfc284c0d7ed799fbad4a3c44325ba36b9c3f3f6f7329f835b22",
                "value": "1"
            },
            {
                "_id": "60f8dc37831c6c19483c1f81",
                "blockhash": "0x01352ff9ef1e6f802fb2b77dd3371c9e9bb2c97533741d42bc2fd933e38ad6cb",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977427823,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "2",
                "tokenId": "R0hPU1T9TNxJRYd8uHTkAoyBtIsupgKItXGjyXNo2aSb0UmbOw==",
                "txid": "0x3b9b49d19ba4d96873c9a371b58802a62e8bb4818c02e474b87c874549dc4cd3",
                "value": "1"
            }
        ],
        "totalCount": 40
    },
    "error": null
}
```



