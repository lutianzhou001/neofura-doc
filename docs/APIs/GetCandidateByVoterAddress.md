## GetCandidateByVoterAddress

To get the transcation of the candidate and other messages by the voter address given.

### input

| 输入参数         | 参数含义       | 类型    | 是否必须  |
| ---------------- | -------------- | ------- |------   |
| VoterAddress | 投票者地址 | string  | 是|

### output

// TODO

### example
```
curl --location --request POST 'http://127.0.0.1:1926' \
--header 'Content-Type: application/json' \
--data-raw '{  
  "jsonrpc": "2.0",
  "method": "GetCandidateByVoterAddress",
  "params": {"VoterAddress":"0xd4772e063e0d9ad7b93e222475c539738879809c"},
  "id": 1
}'
```

