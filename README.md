# be-literal

Attribute equivalent of litter-g

```html
<ul>
<script nomodule be-literal='{
    "input": ["He", "She", "They", "Other"]
}'>
    html`${input.map(i => html`<li>${i}</li>`)}`
</script>
</ul>
```