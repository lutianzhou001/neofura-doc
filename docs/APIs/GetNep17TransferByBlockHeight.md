## GetNep17TransferByBlockHeight

Gets the nep17 transfer by the block height.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight | int | The block height in which the NEP17 transactions are needed |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc":"2.0",
    "method":"GetNep17TransferByBlockHeight",
    "params":{"BlockHeight":69981},
    "id":1
}'
```

### Output

```json
{
  "id": 1,
  "result": {
    "result": [
      {
        "_id": "6147859d7114e0bb4f9b42f1",
        "blockhash": "0x2d3ac96785404ad370f7063db1a11f5b4018ebdd6b80754394360740bcc90c95",
        "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "from": null,
        "frombalance": "0",
        "timestamp": 1627871579237,
        "to": "0x4889dca2933fb56e297035c3ec921af1d0394ba6",
        "tobalance": "131357741660",
        "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "value": "50000000"
      },
      {
        "_id": "6147859d7114e0bb4f9b42f2",
        "blockhash": "0x2d3ac96785404ad370f7063db1a11f5b4018ebdd6b80754394360740bcc90c95",
        "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "from": null,
        "frombalance": "0",
        "timestamp": 1627871579237,
        "to": "0xd9294b3f248b47cca2aa24fb47ece44bb5f9c1fe",
        "tobalance": "171928647550",
        "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "value": "649260"
      },
      {
        "_id": "6147859d7114e0bb4f9b42f3",
        "blockhash": "0x2d3ac96785404ad370f7063db1a11f5b4018ebdd6b80754394360740bcc90c95",
        "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "from": "0x59057af11833590dff6a8f736fcd5fca46e12289",
        "frombalance": "62598983980",
        "timestamp": 1627871579237,
        "to": null,
        "tobalance": "0",
        "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "value": "23100975"
      }
    ],
    "totalCount": 3
  },
  "error": null
}
```



