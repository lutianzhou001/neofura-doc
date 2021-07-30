## GetRawTransactionByTransactionHash

Gets the raw transaction by the transaction hash

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash    |string       |The transaction hash       |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"TransactionHash":"0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68"},
    "method": "GetRawTransactionByTransactionHash"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7feae5a26ad67090d7e07",
        "attributes": [],
        "blockIndex": 102,
        "blockhash": "0xc60ebf0e7610bc4844e297ea3b4216f07ddb526dcc84126c6f5a3ad74bfc8232",
        "blocktime": 1621309747336,
        "hash": "0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68",
        "netfee": 8145220,
        "nonce": 243715009,
        "script": "CwHQBwwUAZelPVEEY0csq+FRLl/HJ9cW+QsMFJKznHeqYPKbV8FzztkX8X/TIabrFMAfDAh0cmFuc2ZlcgwUz3bii9AGLEpHjuNVYQETGfPPpNJBYn1bUjkLAdAHDBSBK+enCCyYQvwqzvpBGLi8WluRiwwUkrOcd6pg8ptXwXPO2Rfxf9MhpusUwB8MCHRyYW5zZmVyDBTPduKL0AYsSkeO41VhARMZ88+k0kFifVtSOQsB0AcMFLFIWPGMdoN0FaYVIcnPaXdudR9VDBSSs5x3qmDym1fBc87ZF/F/0yGm6xTAHwwIdHJhbnNmZXIMFM924ovQBixKR47jVWEBExnzz6TSQWJ9W1I5CwHQBwwUUSCpDoINemxSJkNosYourc3rWM4MFJKznHeqYPKbV8FzztkX8X/TIabrFMAfDAh0cmFuc2ZlcgwUz3bii9AGLEpHjuNVYQETGfPPpNJBYn1bUjkLAdAHDBRDgWaKjFejZCiHNLpFy9GmmW5gqgwUkrOcd6pg8ptXwXPO2Rfxf9MhpusUwB8MCHRyYW5zZmVyDBTPduKL0AYsSkeO41VhARMZ88+k0kFifVtSOQsB0AcMFP7B+bVL5OxH+ySqosxHiyQ/SynZDBSSs5x3qmDym1fBc87ZF/F/0yGm6xTAHwwIdHJhbnNmZXIMFM924ovQBixKR47jVWEBExnzz6TSQWJ9W1I5CwHQBwwUiX1FnExGL5L0lp99cucfN0h7iKQMFJKznHeqYPKbV8FzztkX8X/TIabrFMAfDAh0cmFuc2ZlcgwUz3bii9AGLEpHjuNVYQETGfPPpNJBYn1bUjk=",
        "sender": "NZHf1NJvz1tvELGLWZjhpb3NqZJFFUYpxT",
        "signers": [
            {
                "account": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
                "scopes": "CalledByEntry"
            }
        ],
        "size": 1261,
        "sysfee": 69844460,
        "validUntilBlock": 5861,
        "version": 0,
        "vmstate": "HALT",
        "witnesses": [
            {
                "invocation": "DEDKVRV2t8KPf+2Xc/qflVBNHN4em/QLXI/rL+B3mBaPsL7+jX04GwNIsqtg4jSChCaVp6MDE3QhSnKeJfqQMo57DECNGWZeNtW/sn6H+oxI9vFva8eI2jGyhB/l+4sujXD4zK86deJ5JXxpCXUye+rJkaQVb/n4VeQQqLvH8NfT2B0EDECkFYvtaYJDnXiLJvvkNPGO46que15cpILspaioxOdPR/2+WLtZURU3pv6pqSXCLSq6JRdh7zA69a6eRcybsRomDED33ZaUIUEil3Fc5LTCQRTnzG3N8DO9UT6YTPROvx9GXznOfHdshblk6ees3fQeRrlqSMgC0QPijvkWW+6x7l7RDEDvjr8q1rcWcbT7GwehczFX1Ijeb3XNoKls351qmHJHsFz6R7hZHRr0AQFs3zXWurMI0V9QpmOFnnj4yAqQezqB",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```



