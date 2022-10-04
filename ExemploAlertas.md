
::: warning
#### <i class="fa fa-warning"></i> Caution
If the value for `title` or `body` is `null` or `undefined`, then the corresponding value is not modified on the server. However, if you send an empty string instead then it will **permanently overwrite** the original value.
:::


::: note
## Extensions
Some non-standard Markdown extensions are also supported, such as this informational container, which can also contain **formatting**. Features include:

* Informational block fenced with `::: note` and `:::`
* Warning block fenced with `::: warning` and `:::`
* [x] GitHub-style checkboxes using `[x]` and `[ ]`
* Emoji support :smile: :ship: :cake: using `:smile:` ([cheat sheet](http://www.emoji-cheat-sheet.com/))

These extensions may change in the future as the [CommonMark specification](http://spec.commonmark.org/) defines a [standard extension syntax](https://github.com/jgm/CommonMark/wiki/Proposed-Extensions).
:::
