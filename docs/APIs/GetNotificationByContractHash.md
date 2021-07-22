## GetNotificationByContractHash

Gets the notification by the contract hash

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Limit     | int      | Limit. It is optional |
| Skip |itn |Skip. It is optional |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetNotificationByContractHash"
}'
```

### Output

// TODO
