## GetBlockCount

Gets the latest block number.

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {},
    "method": "GetBlockCount"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "index": 354596
    },
    "error": null
}
```



