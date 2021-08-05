## GetVotesByCandidateAddress

Gets the votes cast to the candidate address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | -------------- |
| CandidateAddress | string | The candidate address to query |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetVotesByCandidateAddress",
  "params": {"CandidateAddress":"0x0bf916d727c75f2e51e1ab2c476304513da59701"},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "60f7fe975a26ad67090d7b79",
        "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
        "isCommittee": true,
        "state": true,
        "votesOfCandidate": "53015863"
    },
    "error": null
}
```

