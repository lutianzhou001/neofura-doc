## GetVotersByCandidateAddress

 Gets the number of voters and their transaction messages by the candidate address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| CandidateAddress | string | The candidate address |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetVotersByCandidateAddress",
  "params": {"CandidateAddress":"0x0bf916d727c75f2e51e1ab2c476304513da59701"},
  "id": 1
}'
```

### Output

// TODO
