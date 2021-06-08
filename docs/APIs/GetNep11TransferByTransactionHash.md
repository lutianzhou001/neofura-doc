## GetNep11TransferByTransactionHash

To get the nep11 transfer (NFT)  by transaction hash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| TransactionHash | 交易Hash | string  | 是|

### output

// TODO

### example

```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11TransferByTransactionHash",
  "params": {"TransactionHash": "0x9a52bbd5b14304b6643074377719dc52eaa1b3458c5860037b5af22126cd44b3",
  "Limit":3 },
  "id": 1
}'
```

