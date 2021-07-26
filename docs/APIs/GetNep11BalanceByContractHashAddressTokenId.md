## GetNep11BalanceByContractHashAddressTokenId

 Gets Nep11Balance(NFT) By the combination of contract script hash, address, and tokenId.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash | string | The contract script hash |
| Address | string | Address |
| TokenId | string | tokenId |
| Limit | int. It is optional | Limit. It is optional |
| Skip | int. It is optional | Skip. It is optional |

### Example

```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11BalanceByContractHashAddressTokenId",
  "params": {"ContractHash": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5","Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","tokenId":"R0hPU1TKCRzQbIhSJ3GEOrKcx2NLIgsUJ25qfBNLzN5p0FWvfA=="},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
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
    "error": null
}
```



