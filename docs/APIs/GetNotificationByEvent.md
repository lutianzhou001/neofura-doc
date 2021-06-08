## GetNotificationByEvent

To get Notification By Event

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Event |事件名称       | string | 是|
| Limit |限制 | Int | 否 |
| Skip |跳过 | Int | 否 |

### output

// TODO

### example

```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNotificationByEvent",
  "params": {"Event": "Transfer" },
  "id": 1
}'
```




