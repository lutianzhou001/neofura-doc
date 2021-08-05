## GetBestBlockHash

Gets the latest block hash.

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetBestBlockHash",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "hash": "0x226844a595780dd2881bbfedbf4ffabe25fcc691969359aa1b7f87a715cdea75"
    },
    "error": null
}
```



