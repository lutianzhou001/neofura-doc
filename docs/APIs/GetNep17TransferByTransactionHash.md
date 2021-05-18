* ## GetNep17TransferByTransactionHash

To get the Nep17Transfer message by transactionhash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| TransactionHash    | 交易hash       | string  | 是|


### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0xeb21ed656bb685d4acf8a9865e6f1b76be47e5569ade72c5224761c58cc2d881"},
    "method": "GetNep17TransferByTransactionHash"
}'

