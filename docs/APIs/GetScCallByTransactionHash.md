## GetScCallByTransactionHash

Gets the transaction details of contract invocation by the transaction hash

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScCallByTransactionHash",
  "params": {"TransactionHash":"0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68" },
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7feae5a26ad67090d7df2",
        "callFlags": "All",
        "contractHash": "0xd2a4cff31913016155e38e474a2c06d08be276cf",
        "hexStringParams": [
            "92b39c77aa60f29b57c173ced917f17fd321a6eb",
            "0197a53d510463472cabe1512e5fc727d716f90b",
            "d007",
            ""
        ],
        "method": "transfer",
        "originSender": "0xeba621d37ff117d9ce73c1579bf260aa779cb392",
        "txid": "0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68"
    },
    "error": null
}
```

