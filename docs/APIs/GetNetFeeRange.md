## GetNetFeeRange

Gets the network fee range.

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNetFeeRange",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "fast": 0,
        "fastest": 0,
        "slow": 0
    },
    "error": null
}
```



