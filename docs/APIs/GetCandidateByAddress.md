## GetCandidateByAddress

Gets the candidate info by the candidate address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Address     | string      | The address of candidate |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetCandidateByAddress",
  "params": {"Address": "0x5b7619d4edd40b1c623495a4a946a833f88bcea8" },
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "_id": "611b7d625052e9839723ad11",
        "candidate": "0x5b7619d4edd40b1c623495a4a946a833f88bcea8",
        "isCommittee": false,
        "state": true,
        "votesOfCandidate": "0"
    },
    "error": null
}
```
