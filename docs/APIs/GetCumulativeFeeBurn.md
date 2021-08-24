## GetCumulativeFeeBurn

Gets the cumulative fee in the last 10 blocks

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetCumulativeFeeBurn",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": [
        {
            "_id": "",
            "feeburn": 3904575793047,
            "result": [
                {
                    "index": 178009,
                    "systemFee": 0
                },
                {
                    "index": 178008,
                    "systemFee": 0
                },
                {
                    "index": 178007,
                    "systemFee": 0
                },
                {
                    "index": 178006,
                    "systemFee": 0
                },
                {
                    "index": 178005,
                    "systemFee": 0
                },
                {
                    "index": 178004,
                    "systemFee": 0
                },
                {
                    "index": 178003,
                    "systemFee": 0
                },
                {
                    "index": 178002,
                    "systemFee": 0
                },
                {
                    "index": 178001,
                    "systemFee": 0
                },
                {
                    "index": 178000,
                    "systemFee": 0
                }
            ]
        }
    ],
    "error": null
}
```
