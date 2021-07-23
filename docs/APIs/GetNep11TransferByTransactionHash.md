## GetNep11TransferByTransactionHash

 Gets the Nep11 transfer (NFT) by the transaction hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11TransferByTransactionHash",
  "params": {"TransactionHash": "0x9a52bbd5b14304b6643074377719dc52eaa1b3458c5860037b5af22126cd44b3",
  "Limit":3 },
  "id": 1
}'
```

### Output

// TODO

