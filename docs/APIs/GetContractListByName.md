## GetContractListByName

Gets the contract list by name(fuzzy search supported).

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Name    | string | The contract name |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetContractListByName",
  "params": {"Name":"FS","Limit":20},
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
                        "sender": "NceCu75mcC9pCu9D8ykj1jyZQGjzXcitGZ"
                    }
                ],
                "createtime": 1627059645757,
                "hash": "0x51cf687eb6625eb1a2b98b0fb4e9d52bdf95f3a6",
                "id": 8,
                "name": "NeoFS"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```
