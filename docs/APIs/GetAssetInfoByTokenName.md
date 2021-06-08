## GetAssetInfoByTokenName

To get AssetInfo by TokenName

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| TokenName |通证名称       | string | 是|

### output

// TODO

### example

```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetAssetInfoByTokenName",
  "params": {"TokenName":"GasToken"},
  "id": 1
}'
```


