> **```ini
>        [ Unsupported features ]
>   # What can't I do with Markdown? #  
> ```**

:paperclips: **Headings**
> Use message links to link to other messages like you would with headers.
> To use stylized headings use a style like the ones on top of these messages, a code block or an image attachment.

:clipboard: **Ordered / Unordered lists**
> Use numbered emojis (:one:, :two:, etc.) to create ordered lists.
> Use an emoji style of your choice to create unordered lists.

:park: **Images**
> Upload files attached to a message or by themselves.

:straight_ruler: **Horizontal Rule**
> Use markdown equivalents. *May require escape characters.*
> Common representations: `----`, `****`, `____`, `- = `

:calendar_spiral: **Tables**
> Use embed fields *with the below format as an example* as a **webhook** or **bot** (25 max, name and value are required).

:clipboard: **Task Lists**
> Use emoji equivelents as substitutes (:white_check_mark:, :negative_squared_cross_mark:, :warning:) or upload your own emojis.

:construction: **No workarounds.**
> Raw HTML Compatibility
> Reference-style links
> Footnotes
> Definition Lists

:no_mobile_phones: **Mobile Incompatibility**
> Colourful code blocks (except for Rust, SQL, python, kotlin, JavaScript)
> Indented code blocks
> Indented links
> Formatted links (code blocks prevent rendering)
> Timestamp mismatch
> Timestamp links

<:gh_prclosed:946189991728521216> **Known style problems**

Discord currently prioritises *some* **unicode** emojis over the escape character within markup.
> This is seen with \:zero: through \:nine:, but remain as the only examples at this time.

Empty space after closing a blockquote with a codeblock. - Reported to be working as intended.
> There's a styling void that comes with codeblocks in blockquotes, something which still remains as a mystery.
> However, for now there is a temporary hotfix we've created to eleviate this if you want - though it'll apply to all blockquotes.
> Try it yourself, with the code below:
> ```css
> blockquote {
>   display: flex;
>   padding-bottom: 5px;
> }
> ```
