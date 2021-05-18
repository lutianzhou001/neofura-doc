## GetExecutionByTrigger

To execution messgae of the trigger

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| Trigger    | 触发       | string  | 是|
| Limit | Limit | int| 否|
| Skip | Skip | int| 否|


### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Trigger":"System"},
    "method": "GetExecutionByTrigger"
}'

