## GetAddressInfoByAddress


Gets the address infomation with the address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address    | string | The user's address |

### Example

```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAddressInfoByAddress",
  "params": {"Address":"0x0bf916d727c75f2e51e1ab2c476304513da59701"},
  "id": 1
}'
```

### Output
```json
{
    "id": 1,
    "result": {
        "_id": "6103a4f0822699ec7ebc63ff",
        "address": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
        "firstusetime": 1468595301000,
        "lastusetime": 1627572748907,
        "transactionssent": 10
    },
    "error": null
}
```



