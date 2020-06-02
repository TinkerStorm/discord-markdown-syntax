# discord-channel-backup

A backup repository for an information channel.

*This environment may hit a ratelimit, increase the sleep interval at [`./post.js#L72`](./post.js#L72).*

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

### Run sequence

*When building your environment config, you can copy this directly into the file property.*

```json
[
	"./content/text-styles/basics.md",
	"./content/text-styles/code-blocks.md",
	"./content/text-styles/combinations.md",

	"./content/code-colors/asciidoc.md",
	"./content/code-colors/autohotkey.md",
	"./content/code-colors/bash.md",
	"./content/code-colors/coffeescript.md",
	"./content/code-colors/cpp.md",
	"./content/code-colors/cs.md",
	"./content/code-colors/css.md",
	"./content/code-colors/diff.md",
	"./content/code-colors/fix.md",
	"./content/code-colors/glsl.md",
	"./content/code-colors/ini.md",
	"./content/code-colors/json.md",
	"./content/code-colors/md.md",
	"./content/code-colors/ml.md",
	"./content/code-colors/prolog.md",
	"./content/code-colors/tex.md",
	"./content/code-colors/xl.md",
	
	"./content/credits.md"
]
```

### Files not used

- `./content/missing.md`
- `./content/additional.md`

## Credits

The credit goes to Wolfiri for the original.
You can join the original server here *it's true origin as a markdown guide*: https://discord.gg/MDnm8TS *not partnered, just accredited and respected for what it is*.