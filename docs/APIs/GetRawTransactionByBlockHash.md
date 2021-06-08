## GetRawTransactionByBlockHash

To RawTransaction by BlockHash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| BlockHash |区块hash       | string | 是|

### output

// TODO

### example

```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetRawTransactionByBlockHash",
  "params": {"BlockHash":"0x0000000000000000000000000000000000000000000000000000000000000000"},
  "id": 1
}'
```



