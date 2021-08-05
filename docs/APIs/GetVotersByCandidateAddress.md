## GetVotersByCandidateAddress

Gets the list of all voters who voted for the candidate's address and related transaction information.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| CandidateAddress | string | The candidate's address |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetVotersByCandidateAddress",
  "params": {"CandidateAddress":"0x0bf916d727c75f2e51e1ab2c476304513da59701"},
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
                "_id": "60f7feb15a26ad67090d7f77",
                "balanceOfVoter": "5000000",
                "blockNumber": 136,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": null,
                "lastVoteTxid": "0x2d2cdff2986b79e84874c69ed2c657bb289532560a45322e00e9b9be08396200",
                "voter": "0xb374baf2ecd30fc82b8ab173e886916fe18898d7"
            },
            {
                "_id": "60f8ee76831c6c194844ac55",
                "balanceOfVoter": "488760",
                "blockNumber": 346648,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": "0x551e3eb8e66223493d43a936e67168eff91945470b2a52e9648b3a3b54017b54",
                "lastVoteTxid": "0x93303a78f4435852f3f1bcbffcc998186fc84b94869ba8af76674f9b8c1fd989",
                "voter": "0x1a352b06731b47976b459a1c2b2c0344ea955c7c"
            },
            {
                "_id": "60f8f8b9831c6c1948496c43",
                "balanceOfVoter": "9700",
                "blockNumber": 221778,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": "0xf50a5af89770e913a07a077b3b87bc231305d24217c7782a1315fa9df4bef5a0",
                "lastVoteTxid": "0x1e9db921225cb95c85d1d588120faba3ea18167dd2e849dd85252f42bf66d6ed",
                "voter": "0xd4772e063e0d9ad7b93e222475c539738879809c"
            },
            {
                "_id": "60f9007b831c6c19484d1805",
                "balanceOfVoter": "47517341",
                "blockNumber": 345476,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": "0x4474ff40db53498dd782de86d7b892075eba6a97ade89493411868bc8036c1e6",
                "lastVoteTxid": "0xb6e6ae11e6b6c685c491267aeffe14724f8c60b2fc5d0f1b3645b3da9073439d",
                "voter": "0x762f8a2bf0e8673c64cc608ba69b9c2a946a188f"
            },
            {
                "_id": "60fa66d86b55861c8df89286",
                "balanceOfVoter": "2",
                "blockNumber": 341138,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": null,
                "lastVoteTxid": "0x135c47855759a3442f11ebeb6355189b5723d3a9f3e526b2ea8c187b9ec923ba",
                "voter": "0x2cab903ff032ac693f8514581665be534beac39f"
            },
            {
                "_id": "60fa66e46b55861c8df89908",
                "balanceOfVoter": "60",
                "blockNumber": 349903,
                "candidate": "0x0bf916d727c75f2e51e1ab2c476304513da59701",
                "candidatePubKey": "023e9b32ea89b94d066e649b124fd50e396ee91369e8e2a6ae1b11c170d022256d",
                "lastTransferTxid": "0x63679214808c7be96f6310163ffd0f04688f98c9f3b9b282178fd3d7bd9aa87e",
                "lastVoteTxid": "0xe19085b8c0dff81fa464d04d3c107798ebdbdd731b6222dc297d55c231122db3",
                "voter": "0x5414edcab5410aac8e13f118b081184cb98e7c88"
            }
        ],
        "totalCount": 6
    },
    "error": null
}
```



