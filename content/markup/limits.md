> **```ini
>                   [Limits]
>   # How do I know if I've gone too far? #  
> ```**

There are a few [content limits](https://discord.com/developers/docs/resources/channel#embed-limits "Embed Limits") Discord has in place.

- **2000 characters** per message.
- **10 files** attached per message.
- **10 embed objects** per message (`embed.*`).
- **256 characeters** per embed title (`embed.*.title`).
- **4096 characters** per embed description (`embed.*.description`).
- **256 characters** per embed author name (`embed.*.author.name`).
- **25 field objects** per embed (`embed.*.fields`).
- **256 characters** per field name (`embed.*.fields.*.name`).
- **1024 characters** per field value (`embed.*.fields.*.value`).
- **2048 characters** per footer text (`embed.*.footer.text`).
- **6000 characters** as a sum cost of all embed attributes per embed.