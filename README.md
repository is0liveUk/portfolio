# hcocd.com

Olivier Charest-Descomme's portfolio. Plain HTML, no build step, hosted free on GitHub Pages.

| Page | File |
| --- | --- |
| Home | `index.html` |
| Zeno (xix3D, 3M, Ford) | `zeno.html` |
| SetSelekta | `setselekta.html` |
| Make (Neon Nine, wraps, sword) | `make.html` |
| About | `about.html` |

- Images and videos live in `media/`. Videos are H.264 MP4 with faststart, ideally under ~5 MB each (GitHub's hard limit is 100 MB per file).
- Each page carries its own `<style>` block; the brand base (colours, Barlow / Barlow Condensed, black header, lime `#C8FF00`) is repeated on every page on purpose so a page can be edited on its own.
- `CNAME` holds the custom domain. Don't delete it.

## Editing

Ask Claude in a session that has this repo attached ("change the Ford caption", "add this photo to Make"). Claude edits the HTML and pushes to `main`; GitHub Pages republishes in about a minute.

Small text fixes can also be done on github.com: open the file, click the pencil, edit, "Commit changes".
