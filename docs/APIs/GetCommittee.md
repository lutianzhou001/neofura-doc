## GetCommittee

Gets Committee

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract address |
| Address    | string | The user address |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{
  "jsonrpc": "2.0",
  "method": "GetCommittee",
  "params": {},
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
                "_id": "60f7fe975a26ad67090d7b7b",
                "candidate": "0xaa606e99a6d1cb45ba34872864a3578c8a668143",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5001000"
            },
            {
                "_id": "60f7fe975a26ad67090d7b79",
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "53015863"
            },
            {
                "_id": "60f7fe975a26ad67090d7b7c",
                "candidate": "0x551f756e7769cfc92115a6157483768cf15848b1",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5099005"
            },
            {
                "_id": "60f7fe975a26ad67090d7b76",
                "candidate": "0x8b915b5abcb81841face2afc42982c08a7e72b81",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5000000"
            },
            {
                "_id": "60f7fe975a26ad67090d7b7a",
                "candidate": "0xce58ebcdad2e8ab1684326526c7a0d820ea92051",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5000000"
            },
            {
                "_id": "60f7ff215a26ad67090d9c81",
                "candidate": "0x84c6634d437d809254f2c118c867dfb99b47e200",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5000000"
            },
            {
                "_id": "60f8021b5a26ad67090e1ebf",
                "candidate": "0x7ba136a00513169d156997937cedff3b28bd6b5a",
                "isCommittee": true,
                "state": true,
                "votesOfCandidate": "5000000"
            }
        ],
        "totalCount": 7
    },
    "error": null
}
```



