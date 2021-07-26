## GetRawTransactionBySender

 Gets the raw transaction by the sender's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Sender    | string | The sender's address |
| Limit     | int | Limit. Optional |
| Skip |itn |Skip. Optional |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"Sender":"NXgxx4sGFB9fdonCdjpweiiPfypMpppDuj"},
    "method": "GetRawTransactionBySender"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "60f7feaf5a26ad67090d7e6c",
                "attributes": [],
                "blockIndex": 112,
                "blockhash": "0x417ab8af8905f6e0cb7c2dc9265deebb4bd431b2cf38d5cd47e620708dc4c60e",
                "blocktime": 1621309906924,
                "hash": "0xb0a8d385e923b65ad61dc11a974e76962bd0dee03d235d3e37284df9861e1424",
                "netfee": 1225520,
                "nonce": 670243011,
                "script": "DCEDAJt1QOEPJWLl/Y+snq7CUWaliybkEjSP9ahpJ7+sIqIRwB8MEXJlZ2lzdGVyQ2FuZGlkYXRlDBT1Y+pAvCg9TQ4FxI6jBbPyoHNA70FifVtS",
                "sender": "NXgxx4sGFB9fdonCdjpweiiPfypMpppDuj",
                "signers": [
                    {
                        "account": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 242,
                "sysfee": 100001045290,
                "validUntilBlock": 5871,
                "version": 0,
                "witnesses": [
                    {
                        "invocation": "DEDvI7TklHQEIBLlL9A0mdIQOrgMjlCOBNDCYOC0chm0mfgFtABckVBgx30t7cWxFyR2rHJvXXgAbp6eSJqmZsvo",
                        "verification": "DCEDAJt1QOEPJWLl/Y+snq7CUWaliybkEjSP9ahpJ7+sIqJBVuezJw=="
                    }
                ]
            },
            {
                "_id": "60f8f270831c6c1948467bb2",
                "attributes": [],
                "blockIndex": 151465,
                "blockhash": "0xebbb80d4e150241de4b3f4a470d39354ed4b55a480d97feaa01feff7ac316720",
                "blocktime": 1623746929583,
                "hash": "0x9384d6d9451566dc57211b9d01d7d5fd821d4fe400d48c5de749a3b65264ffd9",
                "netfee": 1052320,
                "nonce": 617171569,
                "script": "DBZORU8gR2xvYmFsIERldmVsb3BtZW50DAxuZ2QyQHR3aXR0ZXIMB25nZDJAdGcMHmh0dHBzOi8vZ2l0aHViLmNvbS9uZW8tcHJvamVjdAwPc3VwcG9ydEBuZW8ub3JnDAt3d3cubmVvLm9yZwwIaGFuZ3pob3UMBE5HRDIMFIEr56cILJhC/CrO+kEYuLxaW5GLGcAfDAdzZXRJbmZvDBQh+8FBCrrVT1wJ427317iswDtEIEFifVtS",
                "sender": "NXgxx4sGFB9fdonCdjpweiiPfypMpppDuj",
                "signers": [
                    {
                        "account": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 344,
                "sysfee": 167726860,
                "validUntilBlock": 157223,
                "version": 0,
                "witnesses": [
                    {
                        "invocation": "DECdXsZLLzwddqkxAYO6FAfRw/u3z5+ZTrwdBRlAZQ1a2+rInMDMcdg8Rx01Zomtqt04HMFbS6iSEghZ+WIpsKQE",
                        "verification": "DCEDAJt1QOEPJWLl/Y+snq7CUWaliybkEjSP9ahpJ7+sIqJBVuezJw=="
                    }
                ]
            },
            {
                "_id": "60f8f275831c6c1948467e00",
                "attributes": [],
                "blockIndex": 151546,
                "blockhash": "0xa0705f2cc6e4de048305a68e2388d06ca0eb29c6ba182f770df046ba6b602bbe",
                "blocktime": 1623748210487,
                "hash": "0xed8dfa85712bb58c89ea2219c9a909bfd2aa11df3713911a1915c22ecfea2a88",
                "netfee": 1052520,
                "nonce": 1442999536,
                "script": "DBZORU8gR2xvYmFsIERldmVsb3BtZW50DAxuZ2QyQHR3aXR0ZXIMB25nZDJAdGcMHmh0dHBzOi8vZ2l0aHViLmNvbS9uZW8tcHJvamVjdAwPc3VwcG9ydEBuZW8ub3JnDAt3d3cubmVvLm9yZwwJZ3Vhbmd6aG91DAROR0QyDBSBK+enCCyYQvwqzvpBGLi8WluRixnAHwwHc2V0SW5mbwwUIfvBQQq61U9cCeNu99e4rMA7RCBBYn1bUg==",
                "sender": "NXgxx4sGFB9fdonCdjpweiiPfypMpppDuj",
                "signers": [
                    {
                        "account": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 345,
                "sysfee": 165106860,
                "validUntilBlock": 157304,
                "version": 0,
                "witnesses": [
                    {
                        "invocation": "DEBwv4ctsuH5Bj1Wp+xAJ6/84Utr5wl2E9e0wm3PICVxNflnV0gv8rHDzhghXWGsRyG6dBvJj5WEepgCDSdPMZWC",
                        "verification": "DCEDAJt1QOEPJWLl/Y+snq7CUWaliybkEjSP9ahpJ7+sIqJBVuezJw=="
                    }
                ]
            }
        ],
        "totalCount": 3
    },
    "error": null
}
```



