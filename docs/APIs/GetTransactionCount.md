## GetTransactionCount

Gets amount of all transactions till now.

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetTransactionCount",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "total counts": 2400
    },
    "error": null
}
```
