## GetScCallByTransactionHash

 Gets the ScCall by the transaction hash

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| TransactionHash | string | The transaction hash |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScCallByTransactionHash",
  "params": {"TransactionHash":"0xd8f9887c1ed3ceccef42637e70e97ba668760c22e1ceabe5b510ccf70a328c68" },
  "id": 1
}'
```

### Output

// TODO
