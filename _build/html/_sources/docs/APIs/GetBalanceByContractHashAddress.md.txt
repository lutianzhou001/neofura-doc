## GetBalanceByContractHashAddress

Get balance by ContractHash and Address (newest balance)

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| ContractHash    | 合约地址       | string  | 是|
| Address     | 外部地址         | string  |是  |


### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Address":"0x69fdb9f6d614d393e0a0a301855c015b0e8da5bb","ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetBalanceByContractHashAddress"
}'


