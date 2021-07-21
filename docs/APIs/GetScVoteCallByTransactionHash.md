## GetScVoteCallByTransactionHash

 Gets the ScVoteCall by TransactionHash

// especially, this function can also be called by GetScCallByTransactionHash

### Parameters

| Name         | Description       | Type    |    |
| ---------------- | -------------- | ------- |------   |
| TransactionHash | 交易哈希  | string  | 是|

### Output

// TODO

### Example
```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScVoteCallByTransactionHash",
  "params": {"TransactionHash":"0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200" },
  "id": 1
}'
```

