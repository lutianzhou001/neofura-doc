## GetRawTransactionByBlockHash

Gets RawTransaction by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash |string       |The block hash       |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetRawTransactionByBlockHash",
  "params": {"BlockHash":"0x0000000000000000000000000000000000000000000000000000000000000000"},
  "id": 1
}'
```

### Output

// TODO

