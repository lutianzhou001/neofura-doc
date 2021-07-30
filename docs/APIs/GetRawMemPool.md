## GetRawMemPool

Gets the unconfirmed transactions in memory.

### Example
```sh
curl --location --request POST 'http://40.76.139.118:1926' \
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



