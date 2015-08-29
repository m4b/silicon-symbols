# silicon-symbols

Displays a list of symbols, in a particular style.

Supported symbol mode:

* ELF

Supported styles/format:

* nlist (similar to what you see from `nm`)

Submit a PR if you want more.

I'll implement a mach-o version at some point when I have time.

# Usage

```html
<silicon-symbols symbols="[[symbols]]"></silicon-symbols>
```

where symbols is an array of objects whose fields are at least:

1. a number `address` (or `st_value`)
2. a string `type`
3. a string `name`

# Documentation

See you the [documentation](http://m4b.github.io/silicon-symbols) for more information and a demo.
