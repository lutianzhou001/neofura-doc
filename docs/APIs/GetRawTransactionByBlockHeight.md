## GetRawTransactionByBlockHeight

 Gets RawTransaction by the block height

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight |Int       |The block height       |
| Limit |Int |The number of items to return. It is optional and used for paging. |
| Skip |Int |The number of items to skip. It is optional and used for paging. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetRawTransactionByBlockHeight",
  "params": {"BlockHeight": 3300 },
  "id": 1
}'
```

### Output

// TODO



