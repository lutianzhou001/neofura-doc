## GetBalanceByContractHashAddress

Gets the latest balance with the contract script hash and user's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Address     | string   | The external address |

### Example

```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetBalanceByContractHashAddress",
  "params": {"Address":"NUzy2Ns2D35BTdFVqDhUCRoZb1cmix2cXS","ContractHash":"0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f9312bd674c9fe29cb07e0",
        "address": "0x96d5942028891de8e5d866f504b36ff5ae13ab63",
        "asset": "0xef4073a0f2b305a38ec4050e4d3d28bc40ea63f5",
        "balance": "1000000"
    },
    "error": null
}
```

