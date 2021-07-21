## GetContractByContractHash

 Gets the contract MetaData by the contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash |string       |The contract hash       |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetContractByContractHash",
  "params": {"ContractHash": "0xd2a4cff31913016155e38e474a2c06d08be276cf" },
  "id": 1
}'
```

### Output

// TODO

