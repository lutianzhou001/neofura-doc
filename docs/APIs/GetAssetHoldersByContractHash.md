## GetAssetHoldersByContractHash


Gets the asset holders with the contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetHoldersByContractHash",
  "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf","Limit":2},
  "id": 1
}'
```

### Output
```json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "60f8f29e831c6c1948468f33",
                "address": "0x0031db7a58e8d2899e76be0edf21eabc7c7c2eca",
                "asset": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "balance": "99999999"
            },
            {
                "_id": "60f7fff65a26ad67090dc621",
                "address": "0x89768714998d076003e84b60c150b6e97bbafa3c",
                "asset": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "balance": "99998010"
            }
        ],
        "totalCount": 514
    },
    "error": null
}
```

