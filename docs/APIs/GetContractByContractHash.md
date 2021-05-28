## GetContractByContractHash

To get Contract MetaData by Contract Hash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| ContractHash |合约hash       | string  | 是|

### output

// TODO

### example

curl --location --request POST 'http://127.0.0.1:1926' \

--header 'Content-Type: application/json' \

--data-raw '{

  "jsonrpc": "2.0",

  "method": "GetContractByContractHash",

  "params": {"ContractHash": "0xd2a4cff31913016155e38e474a2c06d08be276cf" },

  "id": 1

}'



