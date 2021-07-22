## GetNep11TransferByAddress

 Gets the Nep11 transfer (NFT) by the address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address | string | Address |
| Limit | int | Limit. It is optional |
| Skip | int | Skip. It is optional |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11TransferByAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","Limit":1,"Skip":1},
  "id": 1
}'
```

### Output

// TODO

