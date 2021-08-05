## GetTransferByAddress

Gets the Nep11/Nep17 transfer by address.

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address | string | The address |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |


### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetTransferByAddress",
  "params": {"Address":"0x59057af11833590dff6a8f736fcd5fca46e12289","Limit":2,"Skip":2},
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
                "_id": "6103c9c5766e301307d5f547",
                "blockhash": "0x236495704af0c3ab0d325e8a92f79c7959fae25ba14408871de6a6561457d9c1",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0x59057af11833590dff6a8f736fcd5fca46e12289",
                "frombalance": "48991035360",
                "timestamp": 1627282066487,
                "to": null,
                "tobalance": "0",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "value": "1008964640"
            },
            {
                "_id": "6103c9eb766e301307d5f776",
                "blockhash": "0x645cc9744225cc8222ff18ec112e2e260cbeae0efad1094b9bc98930afb84304",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": "0x59057af11833590dff6a8f736fcd5fca46e12289",
                "frombalance": "48955370165",
                "timestamp": 1627284349560,
                "to": null,
                "tobalance": "0",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "value": "35665195"
            }
        ],
        "totalCount": 21
    },
    "error": null
}
```
