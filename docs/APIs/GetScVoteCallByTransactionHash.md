## GetScVoteCallByTransactionHash

To get the ScVoteCall by TransactionHash

// especially, this function can also be called by GetScCallByTransactionHash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| TransactionHash | 交易哈希  | string  | 是|

### output

// TODO

### example
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

