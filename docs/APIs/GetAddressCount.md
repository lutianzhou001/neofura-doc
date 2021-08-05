## GetAddressCount


Gets the total number of all addresses


### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAddressCount",
  "params": {},
  "id": 1
}'
```

### Output
```json
{
    "id": 1,
    "result": {
        "total counts": 173
    },
    "error": null
}
```



