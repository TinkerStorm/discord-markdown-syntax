# discord-channel-backup

A backup repository for an information channel.

*This environment may hit a ratelimit, increase the sleep interval at [`./post.js#L72`](./post.js#L72).

## Configuration

| Key                   | Type             | Description |
| --------------------- | ---------------- | ----------- |
| `!webhook.*`          | `Object`         |             |
| `webhook.id`          | `string`         |             |
| `webhook.token`       | `string`         |             |
| `defaultPayload?=!{}` | `WebhookMessage` |             |
| `updatePayload?=!{}`  | `WebhookMessage` |             |
| `!files=[]`           | `string[]`       |             |

-   `!` = required
-   `?` = optional

## License

Rights to the files `config.example.json` and `post.js` are licensed to public domain.

## Run Instructions

- `npm install`
- (create and configure `config.json` file)
- `npm start`
