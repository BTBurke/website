# User

## GET /user/search

Search.

| Request | Description              |
| ------- | ------------------------ |
| q       | Query.                   |
| limit   | Limit number of results. |

```shell
curl https://keys.pub/user/search?q=gabriel
```

```json
{
  "users": [
    {
      "id": "gabriel@github",
      "name": "gabriel",
      "kid": "kex1mnseg28xu6g3j4wur7hqwk8ag3fu3pmr2t5lync26xmgff0dtryqupf80c",
      "seq": 1,
      "service": "github",
      "url": "https://gist.github.com/gabriel/ceea0f3b675bac03425472692273cf52",
      "status": "ok",
      "verifiedAt": 1581680761310
    }
  ]
}
```