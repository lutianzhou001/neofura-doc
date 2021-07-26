## GetNep11BalanceByContractHashAddressTokenId

Gets Nep11(NFT) balance by the combination of contract script hash, user's address, and tokenId.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash | string | The contract script hash |
| Address | string | The user's wallet address |
| TokenId | string | tokenId |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11BalanceByContractHashAddressTokenId",
  "params": {"ContractHash": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5","Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","TokenId":"R0hPU1TKCRzQbIhSJ3GEOrKcx2NLIgsUJ25qfBNLzN5p0FWvfA=="},
  "id": 1
}'
```

### Output

// TODO

