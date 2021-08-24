## GetDailyTransactions

Gets the daily transactions in recents days

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Days     | int      | The number of days of transcation count to return. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetDailyTransactions",
  "params": {"Days":1},
  "id": 1
}'

### Output

```json
{
    "id": 1,
    "result": [
        {
            "DailyTransactions": 0,
            "_id": "6123556e40ca90f2da5cbc06"
        }
    ],
    "error": null
}
```
