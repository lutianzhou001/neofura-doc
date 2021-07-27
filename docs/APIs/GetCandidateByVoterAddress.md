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

```json
{
    "id": 1,
    "result": {
        "_id": "60f8f8b9831c6c1948496c43",
        "balanceOfVoter": "9700",
        "blockNumber": 221778,
        "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
        "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
        "lastTransferTxid": "0xf50a5af89770e913a07a077b3b87bc231305d24217c7782a1315fa9df4bef5a0",
        "lastVoteTxid": "0x1e9db921225cb95c85d1d588120faba3ea18167dd2e849dd85252f42bf66d6ed",
        "voter": "0xd4772e063e0d9ad7b93e222475c539738879809c"
    },
    "error": null
}
```

