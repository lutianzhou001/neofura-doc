## GetRawTransactionByTransactionHash

To get raw transaction by transaction hash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| TransactionHash    |交易hash       | string  | 是|

### output

// TODO

### example
```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0x407aff767b88a9acf559bd292d0d3a484a255582868ec1dca11f86131bd4d1f0"},
    "method": "GetRawTransactionByTransactionHash"
}'
```



