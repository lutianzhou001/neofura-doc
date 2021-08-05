## GetNep11TransferByTransactionHash

 Gets the Nep11 (NFT) transfer information by the transaction hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11TransferByTransactionHash",
  "params": {"TransactionHash": "0x502602766c35dfc284c0d7ed799fbad4a3c44325ba36b9c3f3f6f7329f835b22",
  "Limit":3 },
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
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
    "error": null
}
```



