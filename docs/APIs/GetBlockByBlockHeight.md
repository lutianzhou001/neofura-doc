## GetBlockByBlockHeight

 Gets a certain block with the block height (index).

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight    |  int  |  The block height  |

### Example

```shell

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHeight":3823},
    "method": "GetBlockByBlockHeight"
}'
```

### Output

// TODO

