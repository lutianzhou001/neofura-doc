## GetApplicationLogByTransactionHash


Gets the applicationlog by transactionhash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash    | string | The user's address |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetApplicationLogByTransactionHash",
  "params": {"TransactionHash": "0xc704746be18b13abe364dc32eaf03ef6c19da119733436f182febb36c5c34316" },
  "id": 1
}'
```

### Output
```json
{
    "id": 1,
    "result": {
        "_id": "611b7e2e5052e98397240b8c",
        "blockhash": "0xfbf77636644b28dfad651c035f6a0220d46a10b02fe4244c1346048e126df388",
        "exception": null,
        "gasconsumed": 100001045320,
        "notifications": [],
        "timestamp": 1626879742604,
        "trigger": "Application",
        "txid": "0xc704746be18b13abe364dc32eaf03ef6c19da119733436f182febb36c5c34316",
        "vmstate": "HALT"
    },
    "error": null
}
```
