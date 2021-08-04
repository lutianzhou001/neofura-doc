## GetAssetInfoByContractHash

Gets the asset information with the contract script hash.

### Parameters

| Name         | Type   | Description |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"ContractHash":"0xd2a4cff31913016155e38e474a2c06d08be276cf"},
    "method": "GetAssetInfoByContractHash"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fe975a26ad67090d7b65",
        "decimals": 8,
        "firsttransfertime": 1468595301000,
        "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "symbol": "GAS",
        "tokenname": "GasToken",
        "totalsupply": "3028316521052563"
    },
    "error": null
}
```

