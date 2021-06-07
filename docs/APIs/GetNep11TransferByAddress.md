## GetNep11TransferByAddress

To Get Nep11Transfer By Address

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Address | 地址 | string  | 是|
| Limit | 限制 | int | 否 |
| Skip | 跳过 | int | 否 |

### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \

--header 'Content-Type: application/json' \

--data-raw '{

  "jsonrpc": "2.0",

  "method": "GetNep11TransferByAddress",

  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","Limit":1,"Skip":1},

  "id": 1

}'

