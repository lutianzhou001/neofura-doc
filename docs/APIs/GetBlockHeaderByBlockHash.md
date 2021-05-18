## GetBlockHeaderByBlockHash

To get BlockHeader by the input of a blockHash

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| BlockHash    | 区块hash       | string  | 是|


### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHash":"0xaa15bf961c577a9ee9a62774d12d74c6978a03ac782508f93f24aeee452387ff"},
    "method": "GetBlockHeaderByBlockHash"
}'


