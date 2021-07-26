## GetBalanceByContractHashAddress

Gets the latest balance with the contract script hash and user's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Address     | string   | The external address |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Address":"0x69fdb9f6d614d393e0a0a301855c015b0e8da5bb","ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetBalanceByContractHashAddress"
}'
```

### Output

// TODO
