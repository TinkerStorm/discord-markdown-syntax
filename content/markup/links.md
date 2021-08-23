> **[`Links`]**

**[`Escaped Links`]**

> `<https://google.com>`

<https://google.com>

**[`Masked Links`]**

> `[Google](https://google.com)`

[Google](<https://google.com>)

> If using a masked link, you must mask the URL itself and not around it - otherwise it renders the meta embed and the escape characters.

**[`Alt-text / Link title`]**

> `[GitHub](https://github.com "GitHub is where over 65 million developers shape the future of software, together.")`

[GitHub](<https://github.com> "GitHub is where over 65 million developers shape the future of software, together.")

> **Section Notes**
> :one: Link mask / Link title are only supported with a [webhook](<https://discord.dev/resources/webhook#execute-webhook>) or an [embed](<https://discordapp.com/developers/docs/resources/channel#embed-object>).
> :two: If a link title is not provided, the title of the link is used or the URL if no title is provided.
> :three: If using a masked link, you must mask the URL itself and not around it - otherwise it renders the meta embed and the escape characters.