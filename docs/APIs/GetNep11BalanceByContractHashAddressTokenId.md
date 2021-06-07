## GetNep11BalanceByContractHashAddressTokenId

To get Nep11Balance(NFT) By ContractHash and address and tokenId

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| ContractHash | 合约Hash | string  | 是|
| Address | 地址 | string | 是 |
| TokenId | tokenId | string | 是 ｜
| Limit | 限制 | int | 否 |
| Skip | 跳过 | int | 否 |

### output

// TODO

### example

curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11BalanceByContractHashAddressTokenId",
  "params": {"ContractHash": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5","Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","TokenId":"R0hPU1TKCRzQbIhSJ3GEOrKcx2NLIgsUJ25qfBNLzN5p0FWvfA=="},
  "id": 1
}'


