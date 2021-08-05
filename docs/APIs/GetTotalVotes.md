## GetTotalVotes

Gets amount of all votes.

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetTotalVotes",
  "params": {},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "totalvotes": 20112606
    },
    "error": null
}
```
