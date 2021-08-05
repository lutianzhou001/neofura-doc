## GetTransactionList

Gets the list of transactions.

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
  "method": "GetTransactionList",
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
                "_id": "6103e545896a7f59ab1e7ac8",
                "attributes": [],
                "blockIndex": 53416,
                "blockhash": "0xc55e52421505155588635e9375b5462bfcba6652059ff20fd4fc62fd2f1b466f",
                "blocktime": 1627616329647,
                "hash": "0x8803a4dd11b690670bc148e3008b4f9362c1dc22c7871e062f200793289982c4",
                "netfee": 1031760,
                "nonce": 717736816,
                "script": "DARkYXRhAk5hvAAMFEzxBIiQG4dVg53aSJGZBdc4jzffDBRmmdXxSKUGNq3wQcppLAdAe8sD+hTAHwwIdHJhbnNmZXIMFM924ovQBixKR47jVWEBExnzz6TSQWJ9W1IMBGRhdGERDBRM8QSIkBuHVYOd2kiRmQXXOI833wwUZpnV8UilBjat8EHKaSwHQHvLA/oUwB8MCHRyYW5zZmVyDBT1Y+pAvCg9TQ4FxI6jBbPyoHNA70FifVtSDARkYXRhA07zMKZLm7YBDBRM8QSIkBuHVYOd2kiRmQXXOI833wwUZpnV8UilBjat8EHKaSwHQHvLA/oUwB8MCHRyYW5zZmVyDBRbeNQXwVeoUN3AB5KXK/mRzqqiOEFifVtSDARkYXRhAk5hvAAMFEzxBIiQG4dVg53aSJGZBdc4jzffDBRmmdXxSKUGNq3wQcppLAdAe8sD+hTAHwwIdHJhbnNmZXIMFL3dDr7X2ae2Srx3W1WVmkA7qxUUQWJ9W1I=",
                "sender": "NVGUQ1qyL4SdSm7sVmGVkXetjEsvw2L3NT",
                "signers": [
                    {
                        "account": "0xfa03cb7b40072c69ca41f0ad3606a548f1d59966",
                        "scopes": "Global"
                    }
                ],
                "size": 540,
                "sysfee": 35116730,
                "validUntilBlock": 59174,
                "version": 0,
                "witnesses": [
                    {
                        "invocation": "DEDilNae5lgPE1fuwLn9TOkhLNul5ACyfkVLN7cj9Va2eTYvwjYrkDlnAbGGaH+dGcL/U8oEftjrZ5fmViaj9ArX",
                        "verification": "DCEDrQCtTQQyXXSsHZm3oRiqiAzP00uFPaW9tICYC3D7Bm9BVuezJw=="
                    }
                ]
            },
            {
                "_id": "6103e545896a7f59ab1e7ab9",
                "attributes": [],
                "blockIndex": 53416,
                "blockhash": "0xc55e52421505155588635e9375b5462bfcba6652059ff20fd4fc62fd2f1b466f",
                "blocktime": 1627616329647,
                "hash": "0x8333b9f46854cf6ade3b201904bb926ef69abecd3ec28b37784cc09226f5ceba",
                "netfee": 1031760,
                "nonce": 284611277,
                "script": "DARkYXRhAk5hvAAMFEzxBIiQG4dVg53aSJGZBdc4jzffDBRmmdXxSKUGNq3wQcppLAdAe8sD+hTAHwwIdHJhbnNmZXIMFM924ovQBixKR47jVWEBExnzz6TSQWJ9W1IMBGRhdGERDBRM8QSIkBuHVYOd2kiRmQXXOI833wwUZpnV8UilBjat8EHKaSwHQHvLA/oUwB8MCHRyYW5zZmVyDBT1Y+pAvCg9TQ4FxI6jBbPyoHNA70FifVtSDARkYXRhA07zMKZLm7YBDBRM8QSIkBuHVYOd2kiRmQXXOI833wwUZpnV8UilBjat8EHKaSwHQHvLA/oUwB8MCHRyYW5zZmVyDBRbeNQXwVeoUN3AB5KXK/mRzqqiOEFifVtSDARkYXRhAk5hvAAMFEzxBIiQG4dVg53aSJGZBdc4jzffDBRmmdXxSKUGNq3wQcppLAdAe8sD+hTAHwwIdHJhbnNmZXIMFL3dDr7X2ae2Srx3W1WVmkA7qxUUQWJ9W1I=",
                "sender": "NVGUQ1qyL4SdSm7sVmGVkXetjEsvw2L3NT",
                "signers": [
                    {
                        "account": "0xfa03cb7b40072c69ca41f0ad3606a548f1d59966",
                        "scopes": "Global"
                    }
                ],
                "size": 540,
                "sysfee": 35116730,
                "validUntilBlock": 59174,
                "version": 0,
                "witnesses": [
                    {
                        "invocation": "DEDfP8YmUowPgUn9M/izm5evK7EXrSqiGYSom6sJu0HpriUV50adNjTOyMYD83DFXdcTE3miPnzljx0gWT1hINpL",
                        "verification": "DCEDrQCtTQQyXXSsHZm3oRiqiAzP00uFPaW9tICYC3D7Bm9BVuezJw=="
                    }
                ]
            }
        ],
        "totalCount": 2400
    },
    "error": null
}
```
