---
stoplight-id: 8i2x0tc4qumh2
---

# Authentication

Most endpoints require a Bearer token.

You can retrieve such a token by sending your email address and username to the [`https://api.libreview.io/llu/auth/login`](..reference/LibreView.yaml/paths/~1llu~1auth~1login) endpoint.

The response will look like this:

```yaml json_schema
$ref: "../reference/schemas/UserData.yaml"
```