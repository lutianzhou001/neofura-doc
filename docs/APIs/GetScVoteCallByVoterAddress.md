## GetScVoteCallByVoterAddress

 Gets ScVote call by voter address (indicate which candidate does a voter vote to in which block)

### Parameters

| Name         | Description       | Type    |    |
| ---------------- | -------------- | ------- |------   |
| VoterAddress | 投票者hash | string  | 是|

### Output

// TODO

### Example
```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScVoteCallByVoterAddress",
  "params": {"VoterAddress":"0xb374baf2ecd30fc82b8ab173e886916fe18898d7"},
  "id": 1
}'
```

