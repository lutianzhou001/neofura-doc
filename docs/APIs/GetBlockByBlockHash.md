## GetBlockByBlockHash

Gets the corresponding block information by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The block hash |

### Example

```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHash":"0xc7a0f326f7879625daccd5518def63b2d1cb5743948b4cb7333a52e715dbd1a4"},
    "method": "GetBlockByBlockHash"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fea75a26ad67090d7b9b",
        "hash": "0xc7a0f326f7879625daccd5518def63b2d1cb5743948b4cb7333a52e715dbd1a4",
        "index": 4,
        "merkleroot": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "networkFee": 0,
        "nextConsensus": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
        "prevhash": "0x56c2b6074f8a4c2d030b8589ba8aeecc45340843c7b6fb38b36cf87357d99d16",
        "primary": 4,
        "size": 689,
        "systemFee": 0,
        "timestamp": 1621308144079,
        "version": 0,
        "witnesses": [
            {
                "invocation": "DEAGg8j/XyjKp48Wn7Ndb1wFzM4bZZK9c/Qafjm+C3i3eZEX39rGoHXpVDZErJItac1MiMjcKvsn2I0k3eulcBfMDEDeKMH0aDvrcGMZpVSf1lRVGKMlakVPAaiwCRp+1L1tVD2g5prcARe8BopU58qxUKdlubuIAHwjyFDVGEu75iLADEAcia/iYM3hFBt9v2YBIk3TvN0ovzYC8N2pBFrXBGnkz6YUhu9TqqQX1f3afoOgLXgynFZo8ODherspua3k96R2DEDCte+Q7zZLaSe5azUbNaWZOTqJsXZtGTIEoMxPn3jyJ6UGRaugq7YzyrJMndLMN3QY+zb7N5na3SN8zmsH8VrdDEC54Y9rsAtFgd5oYvIjjsmkINvZtm1FqW7cZyMlRORiL9eD5j6d89z64p0RFxE2djNv2csimgrC/wSEE+xHI/0z",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```

