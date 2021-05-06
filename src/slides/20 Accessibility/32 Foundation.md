---
data-auto-animatex: true
---
### Foundation

```hbs
{% raw %}{{#let (unique-id) as |usernameId|}}
  <label for={{usernameId}}>Username</label>
  <input id={{usernameId}} type="text" />
{{/let}}{% endraw %}
```

[Ember `unique-id` helper RFC](https://emberjs.github.io/rfcs/0659-unique-id-helper.html)
