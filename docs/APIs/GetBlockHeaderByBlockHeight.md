## GetBlockHeaderByBlockHeight

Gets the block header by the given block height.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight    | int | The block height |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetBlockHeaderByBlockHeight",
  "params": {"BlockHeight": 20 },
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "611b7d6c5052e9839723adfb",
        "hash": "0xa95208bc9d2939dded2db84161b2069430e80349eafdd0a9a714e3a9130da7ab",
        "index": 20,
        "merkleroot": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "nextConsensus": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
        "prevhash": "0x22ff6bff44dbba4123dc27946ead67b9a7cf36d02ad094ada755a51e52fc07d4",
        "primaryindex": 6,
        "size": 696,
        "timestamp": 1626791714317,
        "version": 0,
        "witnesses": [
            {
                "invocation": "DEC3Zqo8u+s5Ivdv9OU1As9JmtvdoYcMQRJ4h9IGXrjyFAu9XaK9XFjc1dIcOh1TzMAqkVyeARu9Fpikq1vIpnMlDEChqfzsmORJa73Mez8nC5SGL5u68ruex8UMalIazxdChFbrTzeHxg6eOpi1cayEFeLCHbSVtANv3/+M8MVhFZa2DEBl1qqAnYZmd7rTbvTXvGQEtZ3CqIFCNo2X+QkhASdsL3Zr4UqK/n7C5FOAV6x5EzvTPp/2hxIaTdUj51d5n6RtDECtPH/JoQRWhsGMluQamZP04VjohQ14H9Q7odXz+VYuwq5V+YwA0g8Ur4+sES4SP7qN4ds2CBC0SiCyPnJBpMp4DECKNcYg75IX5+4HD0xLixtaurqtilWLKqgLdvgWHhJB+SyCyCUjW7qyvcVuimD9Nm2uuVMJgLy6z+RvuoKRGMJT",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```



