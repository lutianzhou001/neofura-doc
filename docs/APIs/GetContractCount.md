## GetContractCount

Gets the number of all contracts.

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetContractCount",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "total counts": 30
    },
    "error": null
}
```
