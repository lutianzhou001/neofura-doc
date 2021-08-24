## GetNep11TransferCountByAddress

 Gets the Nep17 transfer count by the user's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address | string | The user's address |
| Limit | int | The number of items to return. It is optional and used for paging. |
| Skip | int | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep17TransferCountByAddress",
  "params": {"Address":"0x2e9a0e6a68a4acce23ca14408bb4d0b803425394"},
  "id": 1
}'
```

### Output

````json
{
    "id": 1,
    "result": {
        "total counts": 133
    },
    "error": null
}
```

