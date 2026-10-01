# big-picture-tiles

The tile pyramid behind the live demo of
[big-picture](https://github.com/erik-larsen/big-picture) —
**[erik-larsen.github.io/big-picture](https://erik-larsen.github.io/big-picture/)** —
served from GitHub Pages at `https://erik-larsen.github.io/big-picture-tiles/`.

It is generated output, kept apart from the code so the pictures don't weigh
on every clone of it. It holds a single commit, replaced wholesale whenever
the mosaic is rebuilt (see "In a browser" in the big-picture README).

| path | contents |
| --- | --- |
| `meta.json` | pyramid size, tile size, level count |
| `layout.json` | where each photograph sits in the mosaic |
| `credits.json` | who took each photograph, keyed by file |
| `CREDITS.md` | every photographer, with a link |
| `L{level}/{y}_{x}.jpg` | 260² tiles (256² plus a 2px border), L0 = full resolution |

## Photographs

The photographs are from [Pexels](https://www.pexels.com), used under the
[Pexels licence](https://www.pexels.com/license/), and remain the work of the
photographers credited in `CREDITS.md`. The web viewer names the photographer
of whichever photo is under the pointer.
