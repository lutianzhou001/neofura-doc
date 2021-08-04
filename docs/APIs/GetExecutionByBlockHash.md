## GetExecutionByBlockHash

Gets the block execution message by the block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The block hash |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHash":"0x9eeb9987502c901036207ef56fe11a0ac6e568d9ba569ab741aa771271307232"},
    "method": "GetExecutionByBlockHash"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "60f8d9d0831c6c19483afd47",
                "blockhash": "0x9eeb9987502c901036207ef56fe11a0ac6e568d9ba569ab741aa771271307232",
                "exception": null,
                "gasconsumed": 0,
                "timestamp": 1621782815218,
                "trigger": "OnPersist",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "vmstate": "HALT"
            },
            {
                "_id": "60f8d9d0831c6c19483afd48",
                "blockhash": "0x9eeb9987502c901036207ef56fe11a0ac6e568d9ba569ab741aa771271307232",
                "exception": null,
                "gasconsumed": 0,
                "timestamp": 1621782815218,
                "trigger": "PostPersist",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "vmstate": "HALT"
            }
        ],
        "totalCount": 2
    },
    "error": null
}
```



