## GetNep11OwnedByContractHashAddress

To GetNep11Owned by an address in a certain contracthash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| ContractHash    | 合约地址       | string  | 是|
| Address    | 用户地址地址       | string  | 是|


### output

// TODO

### example
```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByContractHashAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","ContractHash":"0x4a2bb471a07cc7c22e7ff30462287136799aa4f5"},
  "id": 1
}'
```

