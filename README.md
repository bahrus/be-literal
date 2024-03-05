# be-literal

Attribute equivalent of [litter-g](https://github.com/bahrus/litter-g).

```html
<ul be-literal='{
    "input": ["He", "She", "They", "Other"],
    "on": "load"
}' onload="html`${input.map(i => html`<li>${i}</li>`)}`">
</ul>
```