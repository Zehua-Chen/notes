# Escape Code

For complete information, go to
[Wikipedia](https://en.wikipedia.org/wiki/ANSI_escape_code)

- **`ESC` (Escape)**: `\033`
- **`CSI` (Command Sequence Introducer)**: `ESC [`, aka. `\033[`
  - Typically serves as the start of a command sequence
- **`SGR` (Select Graphic Rendition)**: `CGI xxx m`, aka. `\033[xxxm`
  - Used to adjust typography settings, and colors
  - `xxx` is a list with elemented separated by `;`

When parameters are not set, the default values would be used. For example,

```
\033[n;m H]
```

When `n`, and `m` are not included, i.e. `\033[H`, default value of `1` would be
used
