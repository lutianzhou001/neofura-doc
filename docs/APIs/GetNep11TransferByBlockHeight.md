## GetNep11TransferByAddress

Gets the Nep11 (NFT) transfer information by the block height.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight | int | The block height in which the NEP11(NFT) transactions are needed |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc":"2.0",
    "method":"GetNep11TransferByBlockHeight",
    "params":{"BlockHeight":69981},
    "id":1
}'
```

### Output

````json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "6147859d7114e0bb4f9b42f0",
                "blockhash": "0x2d3ac96785404ad370f7063db1a11f5b4018ebdd6b80754394360740bcc90c95",
                "contract": "0x4f628a187e133fa98a5fd0795df3065f219e414e",
                "from": null,
                "frombalance": "0",
                "timestamp": 1627871579237,
                "to": "0x0000000000000000000000000000000000000000",
                "tobalance": "1",
                "tokenId": "U9qaPp0ehFf6afitJ+msIqcM/3T+wEWfvFz1/HOYUzw=",
                "txid": "0x0a8809c34ff72f9ce8b670c584ed6416e1b9ad80ab678b29e400c9dc37bde6be",
                "value": "1"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

