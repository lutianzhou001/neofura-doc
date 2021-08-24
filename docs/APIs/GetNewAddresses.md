## GetNewAddresses

Gets the addresses in recent days

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Days     | int      | The number of days of new addresses to return |


### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNewAddresses",
  "params": {"Days":2},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": [
        {
            "NewAddresses": 0,
            "_id": "61246b9db83452c7b8a2f9ef"
        },
        {
            "NewAddresses": 0,
            "_id": "61246bea9f1b5e7421a9de65"
        }
    ],
    "error": null
}
```



