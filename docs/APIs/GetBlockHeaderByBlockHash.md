## GetBlockHeaderByBlockHash

Gets the block header by the given block hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHash    | string | The block hash |

### Example
```shell
curl --location --request POST '40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHash":"0x990155d73a30dba9ad3a57ec712cfd84ac5016d9a1cc8cd5535c7fa59883074f"},
    "method": "GetBlockHeaderByBlockHash"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fea75a26ad67090d7b84",
        "hash": "0x990155d73a30dba9ad3a57ec712cfd84ac5016d9a1cc8cd5535c7fa59883074f",
        "index": 1,
        "merkleroot": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "nextConsensus": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
        "prevhash": "0x614a807a3e545df0cb5c96d4d387e620e3e34d441f849b9a4033e0b4f906805d",
        "primaryindex": 0,
        "size": 688,
        "timestamp": 1621308004337,
        "version": 0,
        "witnesses": [
            {
                "invocation": "DEDw2e/Z/7WIwZeJVwj+m0fEMJW7ykPaDgPHPazYDWIbe1c53uOY4z4d7AuABCW8VXfvh5tnemKVRnGPRUGFMzRADEAaQDwyXQ3ZohFDp/JbxVBpfaIQ+vrf927ZTXRPAYretQ2BAuo0ql0m5D39pjraM9GjgYNv9w+xy6k8UIQ7NE0IDEB0PSoaEu/z9vkU95ZBPxamGZCYDf3LRf41OqzeYtbAegtLf5Ko/UWJyCN0HN/WearY+s/J8G3BSvILVdXzXwXmDEBNxx3LSxVNj3rz7DPRft0i7hgquTvN+oBKd6mnAxenVgvlSA/7GzLWDBHNjo0dOn1iRpus8PxEi2mei+tbPOdgDEDDvJ7aUmkxDvm/KM69jiq5wsvcllNtqZuTv5+CqquC8UuZRYXSD/2RRrjcW2S720DTJ406uwq4MUntz7WMXFu/",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCEDAgXpzvrqWh38WAryDI1aokaLsBSPGl5GBfxiLIDmBLoMIQIUuvDO6jpm8X5+HoOeol/YvtbNgua7bmglAYkGX0T/AQwhAj6bMuqJuU0GbmSbEk/VDjlu6RNp6OKmrhsRwXDQIiVtDCEDQI3NQWOW9keDrFh+oeFZPFfZ/qiAyKahkg6SollHeAYMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```



