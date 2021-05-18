## GetBlockByBlockHeight

To get a certain block by the blockheight(index)

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| BlockHeight    |   区块高度     |int  | 是|


### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHeight":3823},
    "method": "GetBlockByBlockHeight"
}'


