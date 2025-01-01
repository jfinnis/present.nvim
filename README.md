# `present.nvim`

This is a plugin for presenting markdown files, following along teej_dv's video series.

# Features

Can execute code in lua blocks when you have them in a slide.

```lua
print('Hello world', 37)
```

# Features

Can execute code in javascript blocks when you have them in a slide.

```javascript
console.log({ myField: true, other: false })
```

# Features: Other languages

Can execute code in language blocks when you have them in a slide.

You can configure this with `opts.executors`, Python and Javascript work by
default.

```python
print('this is python')
```

# Usage

```
:PresentStart
```

Use `n` and `p` to navigate markdown slides.

`X` will execute the code block on the page.
