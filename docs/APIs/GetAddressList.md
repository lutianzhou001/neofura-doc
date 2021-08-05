## GetAddressList


Gets the list of addresses

### Parameters

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
  "method": "GetAddressList",
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
                "_id": "6103e11e896a7f59ab1e0700",
                "address": "0x3fb22975ce277844d2ad99f6f125d65931c0f9aa",
                "firstusetime": 1627574920126
            },
            {
                "_id": "6103e112896a7f59ab1e054a",
                "address": "0x933b42dd9777b628ba57088a4debae34bc81fdeb",
                "firstusetime": 1627574199614
            }
        ],
        "totalCount": 173
    },
    "error": null
}
```



