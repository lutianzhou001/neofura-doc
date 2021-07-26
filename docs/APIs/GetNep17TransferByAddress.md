## GetNep17TransferByAddress

Gets all the transfers by the address (including from and to)

### Parameters

| Name | Type | Description |
| -------- | -------- | ------ |
| Address  | string | The user's address |
| Limit    | int | The number of items to return. It is optional and used for paging. |
| Skip     | itn  | The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetNep17TransferByAddress",
  "params": {"Address": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
  "Limit":3 },
  "id": 1

}'
```

### Output

// TODO
