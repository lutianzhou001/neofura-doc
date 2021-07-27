## GetBlockHashByBlockHeight

Gets the block hash by the given block height.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight    | int | The block height |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHeight":3823},
    "method": "GetBlockHashByBlockHeight"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "hash": "0xed8120b29ab55a41a0058887edfc139fcb93e91d043b6986042b12a31d3cb139"
    },
    "error": null
}
```

