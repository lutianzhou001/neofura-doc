## GetNep11OwnedByAddress

Gets the Nep11(NFT) related transaction information occurred at the given address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address    | string | The user's address |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0"},
  "id": 1
}'
```

### Output

// TODO
