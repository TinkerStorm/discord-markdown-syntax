> **```ini
>                 [ Limits ]
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
- **4 image URLs** per embed (`embed.*.image.url`) *when* a URL is present on the initial embed (`embed.*.url`).
> Other image URLs are added in embeds that immediately follow without any extra content (as shown below) - and the URL should be the same to merge them together.

```json
[
  {
    "title": "Collage",
    "description": "This is a collage.",
    "url": "https://discord.com/blog/",
    "image": {
      "url": "https://cdn.discordapp.com/embed/avatars/0.png"
    }
  },
  {
    "url": "https://discord.com/blog/",
    "image": {
      "url": "https://cdn.discordapp.com/embed/avatars/2.png"
    }
  },
  {
    "url": "https://discord.com/blog/",
    "image": {
      "url": "https://cdn.discordapp.com/embed/avatars/3.png"
    }
  },
  {
    "url": "https://discord.com/blog/",
    "image": {
      "url": "https://cdn.discordapp.com/embed/avatars/4.png"
    }
  }
]
```