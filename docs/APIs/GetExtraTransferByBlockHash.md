## GetExtraTranferByBlockHash

Gets the extra transfer(transfer hash is zero) in a block

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The blockhash |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetExtraTransferByBlockHash",
  "params": {"BlockHash":"0x8384c749491f7bc4a819c125b51c9724a752de2dba88f7704072f25083d56269"},
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
                "_id": "611b7d705052e9839723b22c",
                "blockhash": "0x8384c749491f7bc4a819c125b51c9724a752de2dba88f7704072f25083d56269",
                "contract": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
                "from": null,
                "frombalance": "0",
                "timestamp": 1626793603700,
                "to": "0x2e8b81deddfe59f6c1b2f3df1989bba34baa5919",
                "tobalance": "350000000",
                "txid": "0x0000000000000000000000000000000000000000000000000000000000000000",
                "value": "50000000"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

