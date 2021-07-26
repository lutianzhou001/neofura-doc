## GetScVoteCallByTransactionHash

Gets the ScVoteCall by the transaction hash. Especially, this function can also be called by [GetScCallByTransactionHash](GetScCallByTransactionHash.md)

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScVoteCallByTransactionHash",
  "params": {"TransactionHash":"0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200" },
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7feb15a26ad67090d7f76",
        "blockNumber": 136,
        "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
        "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
        "txid": "0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200",
        "voter": "0xb374baf2ecd30fc82b8ab173e886916fe18898d7"
    },
    "error": null
}
```



