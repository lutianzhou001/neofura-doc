## GetScVoteCallByVoterAddress

Gets the voting information by the voter's address.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| VoterAddress | string | The voter's address |

### Example
```shell
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetScVoteCallByVoterAddress",
  "params": {"VoterAddress":"0xb374baf2ecd30fc82b8ab173e886916fe18898d7"},
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
                "_id": "60f7feb15a26ad67090d7f76",
                "blockNumber": 136,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "txid": "0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200",
                "voter": "0xb374baf2ecd30fc82b8ab173e886916fe18898d7"
            }
        ],
        "totalCount": 1
    },
    "error": null
}
```

