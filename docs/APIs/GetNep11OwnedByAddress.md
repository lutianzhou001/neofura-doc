## GetNep11OwnedByAddress

To get the Nep11 owned by address

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Address    | 用户地址       | string  | 是|


### output

// TODO

### example
```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0"},
  "id": 1
}'
```

