## GetNotificationByContractHash

To get notification by contract hash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| ContractHash    | 合约地址       | string  | 是|
| Limit     | Limit         | int  |否  |
| Skip |Skip | itn |否 |

### output

// TODO

### example
```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetNotificationByContractHash"
}'
```

