## GetRawTransactionBySender

To get raw transaction by sender

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Sender    | 发送者地址       | string  | 是|
| Limit     | Limit         | int  |否  |
| Skip |Skip | itn |否 |

### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Sender":"Nd29sK8Wnri8HAAW2vD2APFP8SJJEu3pS4"},
    "method": "GetRawTransactionBySender"
}'



