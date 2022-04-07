> **```ini
>        [ Unsupported features ]
>   # What can't I do with Markdown? #  
> ```**

🖇 **Headings**
> Use message links to link to other messages like you would with headers.
> To use stylized headings use a style like the ones on top of these messages, a code block or an image attachment.

📋 **Ordered / Unordered lists**
> Use numbered emojis (1️⃣, 2️⃣, etc.) to create ordered lists.
> Use an emoji style of your choice to create unordered lists.

🏞 **Images**
> Upload files attached to a message or by themselves.

📏 **Horizontal Rule**
> Use markdown equivalents. *May require escape characters.*
> Common representations: `----`, `****`, `____`, `- = `

📅 **Tables**
> Use embed fields *with the below format as an example* as a **webhook** or **bot** (25 max, name and value are required).

🎯 **Task Lists**
> Use emoji equivelents as substitutes (✅, ❎, ⚠) or upload your own emojis.

🚧 **No workarounds.**
> Raw HTML Compatibility
> Reference-style links
> Footnotes
> Definition Lists

📵 **Mobile Incompatibility**
> Colourful code blocks (except for Rust, SQL, python, kotlin, JavaScript)
> Indented code blocks
> Indented links
> Formatted links (code blocks prevent rendering)
> Timestamp mismatch
> Timestamp links

<:gh_prclosed:946189991728521216> **Known style problems**

Discord currently prioritises *some* **unicode** emojis over the escape character within markup.
> This is seen with \:zero: through \:nine:, but remain as the only examples at this time.

Empty content space after closing a blockquote with a codeblock. - Reported to be working as intended.
> There's a styling void that comes with codeblocks in blockquotes - this doesn't happen if the codeblock is the final content section of the message. We have created a temporary hotfix we've created to eleviate this if you want - though it'll apply to all blockquotes.
> ```css
> blockquote {
>   display: flex;
>   padding-bottom: 5px;
> }
> ```