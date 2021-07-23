## GetCandidateByVoterAddress

Gets the candidate transaction and relevant messages by the voter address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| VoterAddress | string | The voter's wallet address |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetCandidateByVoterAddress",
  "params": {"VoterAddress":"0xd4772e063e0d9ad7b93e222475c539738879809c"},
  "id": 1
}'
```

### Output

// TODO
