## GetNep11OwnedByContractHashAddress

Gets the Nep11(NFT) related transaction information by the given user address and contract script hash.

### Parameters

| Name         | Type   | Description       |
| ---------------- | -------------- | ------- |
| ContractHash    | string | The contract script hash |
| Address    | string | The user address |

### Example
```shell
curl --location --request POST 'http://40.76.139.118:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetNep11OwnedByContractHashAddress",
  "params": {"Address":"0x08f458ba9393d5f4353d1401876ae011f08075f0","ContractHash":"0x3a2bb471a07cc7c22e7ff30462287136799aa4f5"},
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
                "_id": "60f8dc36831c6c19483c1f05",
                "blockhash": "0x9b8f20f6de65f2b287a2ac19137779887a3417973dc3de6ca658d5516220e249",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977154819,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "1",
                "tokenId": "R0hPU1RLW4OfMvf288O5NrolQ8Sj1Lqfee3XwITC3zVsdgImUA==",
                "txid": "0x502602766c35dfc284c0d7ed799fbad4a3c44325ba36b9c3f3f6f7329f835b22",
                "value": "1"
            },
            {
                "_id": "60f8dc37831c6c19483c1fb9",
                "blockhash": "0x61d5bce1dc7be0396cf3ae67904a6fce42e900b9190d88ab28afea4a0a27a15b",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977521221,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "3",
                "tokenId": "R0hPU1TDFaLxzBo0HRZ4LfRCDAgrEb182muzbEgKNn5FtYTSYA==",
                "txid": "0x60d284b5457e360a486cb36bda7cbd112b080c42f42d78161d341accf1a21598",
                "value": "1"
            },
            {
                "_id": "60f8dc38831c6c19483c1ff7",
                "blockhash": "0xca23cd04785444b575e2b872fcb5f18db470b68187af2f842e13468cb1538500",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977629850,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "4",
                "tokenId": "R0hPU1SdI4ctW29uTOlHrlb4VlHgSeX/Jtw5ACVrdFjM1RTk4g==",
                "txid": "0xe2e414d5cc58746b250039dc26ffe549e05156f856ae47e94c6e6f5b2d872371",
                "value": "1"
            },
            {
                "_id": "60f8dc39831c6c19483c20c9",
                "blockhash": "0xdb86bbbdf0d754a891e61eefb89d993670a8d56e6442bbcd779b1e77bf6eb139",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621978028374,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "7",
                "tokenId": "R0hPU1TiRM0mIfJaewNgWIxFs6HqUtwZdzd0MGS2BEOx1btSmg==",
                "txid": "0x9a52bbd5b14304b6643074377719dc52eaa1b3458c5860037b5af22126cd44b3",
                "value": "1"
            },
            {
                "_id": "60f8dc3b831c6c19483c2177",
                "blockhash": "0x1a2875b657aa5a84eea46511d0598595d1d9cca79865674704c8f9d2d09e9398",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621978329648,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "10",
                "tokenId": "R0hPU1Q1wK5c6c3lirlhRkW3Viz2fk/JTEx3/1G+z3quYX82+Q==",
                "txid": "0xf9367f61ae7acfbe51ff774c4cc94f7ef62c56b7454661b98ae5cde95caec003",
                "value": "1"
            },
            {
                "_id": "60f8dc3e831c6c19483c2325",
                "blockhash": "0xde38ab26352340b68749341f32fab570d923bb092f7f72b031f8f79fc54af71b",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621979369011,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "12",
                "tokenId": "R0hPU1QKRcOj2rTfhP5DrLkJN3L3g1qhYaZdwpAObIRci/KQLg==",
                "txid": "0x2e90f28b5c846c0e90c25da661a15a83f7723709b9ac43fe84dfb4daa3c344d6",
                "value": "1"
            },
            {
                "_id": "60f8dc3e831c6c19483c2351",
                "blockhash": "0xcc114ee7de783233b875a4d58c06c1e074edbb86f287ce599398b5cbfead9dd1",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621979431823,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "13",
                "tokenId": "R0hPU1RsrWSrWE7lfat+zah7P4oII66sHnAPc1ALnhQxjSrRjA==",
                "txid": "0x8cd12a8d31149e0b50730f701eacae23088a3f7ba8cd7eab7de54e58ab64ad37",
                "value": "1"
            },
            {
                "_id": "60f8dc37831c6c19483c1f81",
                "blockhash": "0x01352ff9ef1e6f802fb2b77dd3371c9e9bb2c97533741d42bc2fd933e38ad6cb",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977427823,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "2",
                "tokenId": "R0hPU1T9TNxJRYd8uHTkAoyBtIsupgKItXGjyXNo2aSb0UmbOw==",
                "txid": "0x3b9b49d19ba4d96873c9a371b58802a62e8bb4818c02e474b87c874549dc4cd3",
                "value": "1"
            },
            {
                "_id": "60f8dc3a831c6c19483c20fb",
                "blockhash": "0x2a183c49233d21fefe9a8a089e82e72fac28358b04b2a44245eb4e006f9ddd83",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621978107399,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "8",
                "tokenId": "R0hPU1QrC1KGH7ulUyw06/fGMbJCsMgklaOY3Bo8Zheh9++/4g==",
                "txid": "0xe2bfeff7a117663c1adc98a39524c8b042b231c6f7eb342c53a5bb1f86520afb",
                "value": "1"
            },
            {
                "_id": "60f8dc39831c6c19483c2073",
                "blockhash": "0x109be215f25cedd0fe81ba74387b25b50e242466771073872e96a898d7dfc512",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977849481,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "6",
                "tokenId": "R0hPU1Qz0SUSKJZuQwOPCUPd6QdzPXVjqRUPDdQJU1i2Zhpkhg==",
                "txid": "0x86641a66b6585309d40d0f15a963753d7307e9dd43098f03436e96281225d105",
                "value": "1"
            },
            {
                "_id": "60f8dc3a831c6c19483c2127",
                "blockhash": "0x76eaf2a9f6588215b5de00a14426bde7ed187297e6fcc130f69b4c5d54e91d2a",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621978171136,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "9",
                "tokenId": "R0hPU1RgUcI9plF8zxXcAPZZeI44/K4eFMZBIcXcLkvRbRg92Q==",
                "txid": "0xd93d186dd14b2edcc52141c6141eaefc388e7859f600dc15cf7c51a63dc2512f",
                "value": "1"
            },
            {
                "_id": "60f8dc3e831c6c19483c22f3",
                "blockhash": "0x71fbe1fd86855432791d117d83ded6d428246ffaefb796d7fe3ffdc8c5798d28",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621979291246,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "11",
                "tokenId": "R0hPU1Qa2qkJLhkaB/dijmruZWQdcs/N+iadysPWTCe490rHvA==",
                "txid": "0xbcc74af7b8274cd6c3ca9d26facdcf721d6465ee6a8e62f7071a192e09a9d9e7",
                "value": "1"
            },
            {
                "_id": "60f8dc38831c6c19483c203b",
                "blockhash": "0x851c3022b158e196ba5980971a4f43fbc5ab53b8113d29c8cbd0809b6d82db13",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1621977756394,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "5",
                "tokenId": "R0hPU1S8ddOHtnn5+EXKvDyUBsemlpzy2aR+ec00xyG0yr5SAw==",
                "txid": "0x0352becab421c734cd797ea4d9f29c96a6c706943cbcca45f8f979b687d3758f",
                "value": "1"
            },
            {
                "_id": "60f8dc86831c6c19483c42bb",
                "blockhash": "0x4211c4bd074dff7626d5ed216ace565178188cb0b55fa3e1e48f0a5646e94b28",
                "contract": "0x3a2bb471a07cc7c22e7ff30462287136799aa4f5",
                "from": null,
                "frombalance": "0",
                "timestamp": 1622000593035,
                "to": "0x08f458ba9393d5f4353d1401876ae011f08075f0",
                "tobalance": "14",
                "tokenId": "R0hPU1TKCRzQbIhSJ3GEOrKcx2NLIgsUJ25qfBNLzN5p0FWvfA==",
                "txid": "0x7caf55d069decc4b137c6a6e27140b224b63c79cb23a84712752886cd01c0994",
                "value": "1"
            }
        ],
        "totalCount": 14
    },
    "error": null
}
```

