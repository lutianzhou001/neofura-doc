## GetScCallByContractHashAddress

Gets ScCall by an address in a certain contract

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract address |
| Address    | string | The user address |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScCallByContractHashAddress",
  "params": {"Address":"0xeba621d37ff117d9ce73c1579bf260aa779cb392","ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
  "id": 1
}'
```

### Output

// TODO
