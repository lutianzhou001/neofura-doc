## GetBlockInfoByBlockHash

Gets the block info by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The block hash |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetBlockInfoByBlockHash",
  "params": {"BlockHash":"0x8384c749491f7bc4a819c125b51c9724a752de2dba88f7704072f25083d56269"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "611b7d705052e9839723b232",
        "hash": "0x8384c749491f7bc4a819c125b51c9724a752de2dba88f7704072f25083d56269",
        "index": 140,
        "merkleroot": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "nep11count": 0,
        "nep17count": 1,
        "networkFee": 0,
        "nextConsensus": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
        "nonce": "8010367908061026749",
        "prevhash": "0x910d778f6fbfd4d750b000ab87a36e488e18675d68e9f1733a8b91919815673f",
        "primary": 0,
        "size": 697,
        "systemFee": 0,
        "timestamp": 1626793603700,
        "transactioncount": 0,
        "version": 0,
        "witnesses": [
            {
                "invocation": "DEBBNADpSJgQxcDtq0m12xN1L8zww+/q9fWI5dvXTGaRml3NhdQfnM73OMxt3VsCFhG+osAQsg30+kC6ZlPjwXgJDEA2iIU+ykjvqqsnPncnC+oPdLJXQD2u/GjwSUfbk3pwrnZ8Sj28fpVUaexvuWNm/LCcS2SGSIsz7bsFqECmZl6oDECXMrj3ntXlAh5lTIYUyXuFBcBeNfcXAe9tOzElgDCg3s7PSgHyhUZ/QhHZ0YH88MLp7Mt4FpKRr1fEK7e3K6ozDEBeDIuhMnfyieB/7Yv6CWW94i4qIDXCAZBNLR2zZZbXkxp65hqTUPegfVIGKGXmIhLkKZM9WKGzA0TLB92L6s5PDECjLwJIl6rAgPs/rlT6ISYf9f03P5xPlcoYeU+hzc+eL2ZrSVCKH8wOsSaH2RsrgEh98ips1KLSFslBWOL/e03l",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```
