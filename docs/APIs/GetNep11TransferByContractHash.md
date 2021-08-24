## GetNep11TransferByContractHash

 Gets the Nep11 (NFT) transfer information by the user address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash | string | The contract script hash |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep11TransferByContractHash",
  "params": {"ContractHash":"0x4f628a187e133fa98a5fd0795df3065f219e414e","Limit":2},
  "id": 1
}'
```

### Output

````json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "611f56a1625ff158d7cc581e",
                "blockhash": "0x2833d04f56ec5187c6cef1c415e8a9bd77970fb4d4d4fbcd3e4c22a7dd9b2ba6",
                "contract": "0x4f628a187e133fa98a5fd0795df3065f219e414e",
                "from": null,
                "frombalance": "1",
                "timestamp": 1627997424700,
                "to": "0x0000000000000000000000000000000000000000",
                "tobalance": "1",
                "tokenId": "+nP6+q1lkLy6ibAdGfG3qKCfGNVnHvrMOTj+5IIgmXo=",
                "txid": "0x97b3a25f41613380b2c3477236a659ba94e4481244009242b2bc8cc59db4f1ed",
                "value": "1"
            },
            {
                "_id": "611f566f625ff158d7cc3f9b",
                "blockhash": "0x2712422b9986ab230f878f42e8b9be0c6054de6736d41659e3c467b5d3281cb8",
                "contract": "0x4f628a187e133fa98a5fd0795df3065f219e414e",
                "from": null,
                "frombalance": "1",
                "timestamp": 1627979228877,
                "to": "0x0000000000000000000000000000000000000000",
                "tobalance": "1",
                "tokenId": "C85LNUKkJNHu802Yd0HgDxI3JJoJ/j6X/Rl0Cb8ky4c=",
                "txid": "0x8cb052299769ed206a10aa038bba6473f7c327d31dca470a445c653270bf49a9",
                "value": "1"
            }
        ],
        "totalCount": 8
    },
    "error": null
}
```

