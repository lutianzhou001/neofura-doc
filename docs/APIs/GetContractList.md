## GetContractList

Gets the contract list.

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetContractList",
  "params": {"Limit":2,"Skip":2},
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
                "Transaction": [
                    {
                        "sender": "NVGUQ1qyL4SdSm7sVmGVkXetjEsvw2L3NT"
                    }
                ],
                "createtime": 1626850758657,
                "hash": "0x618d44dc3af16c6120dbf65402024f40a04f772a",
                "id": 1,
                "name": "CCMC"
            },
            {
                "Transaction": [
                    {
                        "sender": "NVGUQ1qyL4SdSm7sVmGVkXetjEsvw2L3NT"
                    }
                ],
                "createtime": 1626850898000,
                "hash": "0x4487494dac2f7eb68bdae009cacd6de88243e542",
                "id": 2,
                "name": "Proxy"
            }
        ],
        "totalCount": 30
    },
    "error": null
}
```
