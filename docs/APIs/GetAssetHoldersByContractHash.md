## GetAssetHoldersByContractHash

Gets asset holders by the contract hash.

### Parameters

| Parameter         | Type      | Description    |   |
| ---------------- | -------------- | ------- |------   |
| ContractHash    | string      | The contract script hash  | |
| Limit     | int         | Limit  |Optional  |
| Skip |itn | Skip |Optional |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetAssetHoldersByContractHash"
}'
```

### Output

// TODO

