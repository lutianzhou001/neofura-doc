## GetCandidate

Gets the candidate.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| Limit     | int      | The number of items to return. It is optional and used for paging. |
| Skip |int |The number of items to skip. It is optional and used for paging. |

### Example
```shell
curl --location --request POST '127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetCandidate",
  "params": {"Limit":6},
  "id": 1
}'
```

### Output

```json
{
    "id": 1,
    "result": {
        "result": [
            {
                "_id": "6103a4f0822699ec7ebc640a",
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "3000097"
            },
            {
                "_id": "6103a4f0822699ec7ebc640b",
                "candidate": "0xce58ebcdad2e8ab1684326526c7a0d820ea92051",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "2000272"
            },
            {
                "_id": "6103a4f0822699ec7ebc6407",
                "candidate": "0xd9294b3f248b47cca2aa24fb47ece44bb5f9c1fe",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "2000000"
            },
            {
                "_id": "6103a4f0822699ec7ebc6403",
                "candidate": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "2000000"
            },
            {
                "_id": "6103a4f0822699ec7ebc6412",
                "candidate": "0xaa606e99a6d1cb45ba34872864a3578c8a668143",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "2000000"
            },
            {
                "_id": "6103a4f0822699ec7ebc6413",
                "candidate": "0x551f756e7769cfc92115a6157483768cf15848b1",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "2000000"
            }
        ],
        "totalCount": 37
    },
    "error": null
}
```



