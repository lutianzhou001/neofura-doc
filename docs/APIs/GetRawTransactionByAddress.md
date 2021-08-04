## GetRawTransactionByAddress

Gets the raw transaction by the sender's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address | string | The sender's address |
| Limit     | int | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetRawTransactionByAddress",
  "params": {"Address": "0x0bf916d727c75f2e51e1ab2c476304513da59701"},
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
                "_id": "60f7feaf5a26ad67090d7e5f",
                "attributes": [],
                "blockIndex": 111,
                "blockhash": "0xf793c52811a46965a938b767f28508bb53c20dc33d2e2268e92584736cd10143",
                "blocktime": 1621309890228,
                "hash": "0xf1e02c4a3c3ba96b12a58d8feb13e688bb3f42499ad02324fd9cfd0159d7a29f",
                "netfee": 1225520,
                "nonce": 580636858,
                "script": "DCECPpsy6om5TQZuZJsST9UOOW7pE2no4qauGxHBcNAiJW0RwB8MEXJlZ2lzdGVyQ2FuZGlkYXRlDBT1Y+pAvCg9TQ4FxI6jBbPyoHNA70FifVtS",
                "sender": "NL4PXTc8dxjBca8FEkJYCEgDWL98ZnzcnV",
                "signers": [
                    {
                        "account": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 242,
                "sysfee": 100001045290,
                "validUntilBlock": 5870,
                "version": 0,
                "vmstate": "HALT",
                "witnesses": [
                    {
                        "invocation": "DEBcVZXGOhc3UBpA3QVnqxpgtdrXHfGx2zAknr7vviOdM0nTe7ZLbKwYaprkRnlKPlFaOLkuVAbQ1LjyDORyuFzS",
                        "verification": "DCECPpsy6om5TQZuZJsST9UOOW7pE2no4qauGxHBcNAiJW1BVuezJw=="
                    }
                ]
            },
            {
                "_id": "60f7feb25a26ad67090d808b",
                "attributes": [],
                "blockIndex": 163,
                "blockhash": "0xa4c6e2de9a6e212e10a51f60e1a8e255c0d72c366135f222161f76d5c8cd9841",
                "blocktime": 1621310734807,
                "hash": "0x939a8294f85902c1b80b2472da1ad6edb7d9289be92a5fd8699fa72c0ec2a637",
                "netfee": 8723740,
                "nonce": 864046580,
                "script": "CwKA8PoCDBSPGGqUKpybpotgzGQ8Z+jwK4ovdgwUkrOcd6pg8ptXwXPO2Rfxf9MhpusUwB8MCHRyYW5zZmVyDBT1Y+pAvCg9TQ4FxI6jBbPyoHNA70FifVtSOQ==",
                "sender": "NL4PXTc8dxjBca8FEkJYCEgDWL98ZnzcnV",
                "signers": [
                    {
                        "account": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                        "scopes": "None"
                    },
                    {
                        "account": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 856,
                "sysfee": 9977780,
                "validUntilBlock": 5922,
                "version": 0,
                "vmstate": "HALT",
                "witnesses": [
                    {
                        "invocation": "DEDfuizCeGiwqBSgl+hzrH6aS/gwkV86F7MLsFSwao7HxIvlYgkw+/tQpdtv7nWy8E3s00li+RN4h5LdsRRZlkvs",
                        "verification": "DCECPpsy6om5TQZuZJsST9UOOW7pE2no4qauGxHBcNAiJW1BVuezJw=="
                    },
                    {
                        "invocation": "DECNfNItP76l+Lxqc6sD3wJ3138kTsYGQtOMYyE5IVleoIbLx0vW65bZE+ZOzfNtIv97MA3/uE+7YSGNnFncKDDTDECDDT7zMct6Zo+LvyfXX/GKJdBDPJ47NE1pjBT8Kx/gCMHUJ7SYZxDTxnHVIHRdWlUpuCgkYXPYUhlPJKHgs3l7DECV5VTrkIBAyyvFJ+sCN+Vg1bfHDXpRX4B43XuDHlTRg0Bi/jXxYB9j9UjhiTWa7DfoxtiN6MDuy8tJ6qOtZe9BDEAjJnNFZodHJGxTvwanEk09eW2YuZYOI/HXqnNmR7VeOTAJi5ZMtzZtifio/JzOyrsPqgoqEv6qQMb1Px1Zh9pPDEArrdgB34cHiHV1sacGQE0zjjPQmOme2uxw8RWilzYQnuuGqaiRidCehooA54uSDMjMQMnRwEaCNUZ8hMOgP3OO",
                        "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
                    }
                ]
            },
            {
                "_id": "60f8f260831c6c1948467933",
                "attributes": [],
                "blockIndex": 151376,
                "blockhash": "0x231b4f4556fbd02ea688f193535115c5bf1e6c31f531f397ebdabc0de6f8a2d2",
                "blocktime": 1623745513665,
                "hash": "0x00048875cc67503b0ffcb729090654a5b5c4266fe46175002c2c9351e0a4e7bb",
                "netfee": 1052320,
                "nonce": 1527407256,
                "script": "DBZORU8gR2xvYmFsIERldmVsb3BtZW50DAxuZ2QxQHR3aXR0ZXIMB25nZDFAdGcMHmh0dHBzOi8vZ2l0aHViLmNvbS9uZW8tcHJvamVjdAwPc3VwcG9ydEBuZW8ub3JnDAt3d3cubmVvLm9yZwwIU2hhbmdoYWkMBE5HRDEMFAGXpT1RBGNHLKvhUS5fxyfXFvkLGcAfDAdzZXRJbmZvDBQh+8FBCrrVT1wJ427317iswDtEIEFifVtS",
                "sender": "NL4PXTc8dxjBca8FEkJYCEgDWL98ZnzcnV",
                "signers": [
                    {
                        "account": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                        "scopes": "CalledByEntry"
                    }
                ],
                "size": 344,
                "sysfee": 144576010,
                "validUntilBlock": 157135,
                "version": 0,
                "vmstate": "HALT",
                "witnesses": [
                    {
                        "invocation": "DECOkqtNYlvnKsaYFvK+2/uzhb1Jp6rx8SNW1EzybgPFyZI+1aH4ws7Htyl7pHUoExoJCEHqJN5yA9UUZiYWsm8M",
                        "verification": "DCECPpsy6om5TQZuZJsST9UOOW7pE2no4qauGxHBcNAiJW1BVuezJw=="
                    }
                ]
            }
        ],
        "totalCount": 3
    },
    "error": null
}
```



