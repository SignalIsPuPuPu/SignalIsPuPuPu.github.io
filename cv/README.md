# Academic CV

This directory contains an academic CV starter based on
[Awesome-CV](https://github.com/posquit0/Awesome-CV), licensed under LPPL 1.3c.
The upstream license is preserved in `LICENSE-AWESOME-CV`.

## Edit

1. Replace the personal information near the top of `cv.tex`.
2. Replace the example entries in `sections/` with your own information.
3. Add, remove, or reorder `\input{sections/...}` lines in `cv.tex`.

## Build

From this directory, run:

```sh
make pdf
```

LuaLaTeX is the default engine. You can also upload the whole `cv/` directory
to Overleaf and set `cv.tex` as the main document.

To publish the finished CV on the website, copy `cv.pdf` to `../files/cv.pdf`
and link it from `_pages/cv.md`.
