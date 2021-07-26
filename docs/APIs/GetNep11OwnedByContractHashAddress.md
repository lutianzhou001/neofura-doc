## GetNep11OwnedByContractHashAddress

Gets the Nep11(NFT) related transaction information by the given user address and contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Address    | string | The user address |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByContractHashAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","ContractHash":"0x4a2bb471a07cc7c22e7ff30462287136799aa4f5"},
  "id": 1
}'
```

### Output

// TODO
