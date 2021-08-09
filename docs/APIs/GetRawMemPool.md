## GetRawMemPool

Gets the unconfirmed transactions in memory.

### Example
```sh
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetRawMemPool",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": [],
    "error": null
}
```



