## GetScVoteCallByTransactionHash

Gets the ScVoteCall by the transaction hash. Especially, this function can also be called by [GetScCallByTransactionHash](GetScCallByTransactionHash.md)

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScVoteCallByTransactionHash",
  "params": {"TransactionHash":"0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200" },
  "id": 1
}'
```

### Output

// TODO
