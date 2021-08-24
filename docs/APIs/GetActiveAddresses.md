## GetActiveAddress


Gets the active addresses count in several days

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Days    | int | gets active addresses count in serveral days |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Days":1},
    "method": "GetActiveAddresses"
}'
```

### Output
```json
{
    "id": 1,
    "result": [
        {
            "ActiveAddresses": 0,
            "_id": "6123556e40ca90f2da5cbc05"
        }
    ],
    "error": null
}
```
