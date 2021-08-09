## GetNep11BalanceByContractHashAddress

 Gets Nep11(NFT) balance By the contract script hash and user's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash | string | The contract script hash |
| Address | string | The user's wallet address |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip It is optional and used for paging. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11BalanceByContractHashAddress",
  "params": {"ContractHash": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5","Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","Limit":3},
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
                "balance": "14",
                "latesttx": {
                    "_id": "60f8dc86831c6c19483c42bb",
                    "blockhash": "0x4211c4bd074dff7626d5ed216ace565178188cb0b55fa3e1e48f0a5646e94b28",
                    "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                    "from": null,
                    "frombalance": "0",
                    "timestamp": 1622000593035,
                    "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                    "tobalance": "14",
                    "tokenId": "R0hPU1TKCRzQbIhSJ3GEOrKcx2NLIgsUJ25qfBNLzN5p0FWvfA==",
                    "txid": "0x7caf55d069decc4b137c6a6e27140b224b63c79cb23a84712752886cd01c0994",
                    "value": "1"
                }
            },
            {
                "balance": "13",
                "latesttx": {
                    "_id": "60f8dc3e831c6c19483c2351",
                    "blockhash": "0xcc114ee7de783233b875a4d58c06c1e074edbb86f287ce599398b5cbfead9dd1",
                    "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                    "from": null,
                    "frombalance": "0",
                    "timestamp": 1621979431823,
                    "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                    "tobalance": "13",
                    "tokenId": "R0hPU1RsrWSrWE7lfat+zah7P4oII66sHnAPc1ALnhQxjSrRjA==",
                    "txid": "0x8cd12a8d31149e0b50730f701eacae23088a3f7ba8cd7eab7de54e58ab64ad37",
                    "value": "1"
                }
            },
            {
                "balance": "12",
                "latesttx": {
                    "_id": "60f8dc3e831c6c19483c2325",
                    "blockhash": "0xde38ab26352340b68749341f32fab570d923bb092f7f72b031f8f79fc54af71b",
                    "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                    "from": null,
                    "frombalance": "0",
                    "timestamp": 1621979369011,
                    "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                    "tobalance": "12",
                    "tokenId": "R0hPU1QKRcOj2rTfhP5DrLkJN3L3g1qhYaZdwpAObIRci/KQLg==",
                    "txid": "0x2e90f28b5c846c0e90c25da661a15a83f7723709b9ac43fe84dfb4daa3c344d6",
                    "value": "1"
                }
            }
        ],
        "totalCount": 14
    },
    "error": null
}
```



