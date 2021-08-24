## GetVmStateByTransactionHash

Gets the vmstate by transactionhash.

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transactionhash |



### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetVmStateByTransactionHash",
  "params": {"TransactionHash":"0x131dc315a3301c13d019f70515f7120d4a4ed065e67cc90fabe1673422f404ff"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "vmstate": "HALT"
    },
    "error": null
}
```
