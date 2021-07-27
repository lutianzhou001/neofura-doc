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

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fe975a26ad67090d7b63",
        "createTxid": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "createtime": 1468595301000,
        "hash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "id": -6,
        "manifest": "{\"name\":\"GasToken\",\"groups\":[],\"features\":{},\"supportedstandards\":[\"NEP-17\"],\"abi\":{\"methods\":[{\"name\":\"balanceOf\",\"parameters\":[{\"name\":\"account\",\"type\":\"Hash160\"}],\"returntype\":\"Integer\",\"offset\":0,\"safe\":true},{\"name\":\"decimals\",\"parameters\":[],\"returntype\":\"Integer\",\"offset\":7,\"safe\":true},{\"name\":\"refuel\",\"parameters\":[{\"name\":\"account\",\"type\":\"Hash160\"},{\"name\":\"amount\",\"type\":\"Integer\"}],\"returntype\":\"Void\",\"offset\":14,\"safe\":false},{\"name\":\"symbol\",\"parameters\":[],\"returntype\":\"String\",\"offset\":21,\"safe\":true},{\"name\":\"totalSupply\",\"parameters\":[],\"returntype\":\"Integer\",\"offset\":28,\"safe\":true},{\"name\":\"transfer\",\"parameters\":[{\"name\":\"from\",\"type\":\"Hash160\"},{\"name\":\"to\",\"type\":\"Hash160\"},{\"name\":\"amount\",\"type\":\"Integer\"},{\"name\":\"data\",\"type\":\"Any\"}],\"returntype\":\"Boolean\",\"offset\":35,\"safe\":false}],\"events\":[{\"name\":\"Transfer\",\"parameters\":[{\"name\":\"from\",\"type\":\"Hash160\"},{\"name\":\"to\",\"type\":\"Hash160\"},{\"name\":\"amount\",\"type\":\"Integer\"}]}]},\"permissions\":[{\"contract\":\"*\",\"methods\":\"*\"}],\"trusts\":[],\"extra\":null}",
        "name": "GasToken",
        "nef": "{\"magic\":860243278,\"compiler\":\"neo-core-v3.0\",\"tokens\":[],\"script\":\"EEEa93tnQBBBGvd7Z0AQQRr3e2dAEEEa93tnQBBBGvd7Z0AQQRr3e2dA\",\"checksum\":529571427}",
        "updatecounter": 0
    },
    "error": null
}
```



