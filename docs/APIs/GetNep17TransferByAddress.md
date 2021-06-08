## GetNep17TransferByAddress

To get the all the transfers by inputing address (including from and to)

### input

| 输入参数 | 参数含义 | 类型   | 是否必须 |
| -------- | -------- | ------ | -------- |
| Address  | 地址     | string | 是       |
| Limit    | Limit    | int    | 否       |
| Skip     | Skip     | itn    | 否       |

### output

// TODO

### example
```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep17TransferByAddress",
  "params": {"Address": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
  "Limit":3 },
  "id": 1

}'
```

