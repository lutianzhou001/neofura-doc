## GetAssetCount


Gets the number of all assets


### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetCount",
  "params": {},
  "id": 1
}'
```

### Output
```json
{
    "id": 1,
    "result": {
        "total counts": 17
    },
    "error": null
}
```



