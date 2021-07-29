## GetBlockByBlockHeight

Gets the corresponding block information by the given block height (index).

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| BlockHeight    |  int  |  The block height  |

### Example

```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
    "jsonrpc": "2.0",
    "id": 1,
    "params": {"BlockHeight":3823},
    "method": "GetBlockByBlockHeight"
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f800985a26ad67090dd8a7",
        "hash": "0xed8120b29ab55a41a0058887edfc139fcb93e91d043b6986042b12a31d3cb139",
        "index": 3823,
        "merkleroot": "0x0000000000000000000000000000000000000000000000000000000000000000",
        "networkFee": 0,
        "nextConsensus": "0x0478ad926a22ac8cc2ae0afc57cc460805bce77c",
        "prevhash": "0x8f5e0811be7d6c79f069eb07589829c9599f5b0dc2bb76f7c93e1b7cc6aff610",
        "primary": 1,
        "size": 689,
        "systemFee": 0,
        "timestamp": 1621369096907,
        "version": 0,
        "witnesses": [
            {
                "invocation": "DEBZdgqWmKB3l6RcrSBZ5I68dbm+xwaS6PrOwzIzwZhjbL1656HEGU8elTXgsfepITIrZbu2zTKdht/0OHTsvOl0DEDTfr0hxooCt1m2kdlaAUBVwF0LyRqwzeQ5GmYQwiD6JkUcQ+2tZXSrDUqSr7ogfI7VtWUyPAnPNis7l6aRJ+PRDECOtBIslCvOyrx1Q32DuzOcusilkpagwcF0SIleWNuIrPyALZtINqiIrHPEzY9wzMC22Rxr9tZlcJQYovKURdjTDEBUf7llCylqJO40vO6pCZA5nr3dMBe310mcLHBbI/3dC0wBEVXOjpYkZGPc8b41aQBulwZ/AC2RBKkK04i7o0VqDEB8Lq82/VaxNQNwUFt5ffrvTE77kpag+Aigw4xGZe7UpZwxOy6kKRGUwx2iulI9GmV1j1L5mjPCAN5kF/ekF2mx",
                "verification": "FQwhAwCbdUDhDyVi5f2PrJ6uwlFmpYsm5BI0j/WoaSe/rCKiDCECFLrwzuo6ZvF+fh6DnqJf2L7WzYLmu25oJQGJBl9E/wEMIQI+mzLqiblNBm5kmxJP1Q45bukTaejipq4bEcFw0CIlbQwhA0CNzUFjlvZHg6xYfqHhWTxX2f6ogMimoZIOkqJZR3gGDCEDkYlZM7MIn1oLHYupZ+/9xpjvHxDscAru8rOX0WK95DUMIQKng0vpsy4pgdFXy1u9OstCz9EepcOxAiTXpE6YxZEPGwwhAroscPWZbzV6QxmHBYWfriz+oT4RcpYoAHcrPViKnUq9F0Ge0Nw6"
            }
        ]
    },
    "error": null
}
```



