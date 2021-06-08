## GetAssetHeldByAddress

To get asset holders by contract hash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Address    | 合约地址       | string  | 是|
| Limit     | Limit         | int  |否  |
| Skip |Skip | int |否 |

### output

// TODO

### example


```
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Address":"0x3555537a8d50d0a7738a42ae605f86708e73d0ac"},
    "method": "GetAssetsHeldByAddress"
}'
```


