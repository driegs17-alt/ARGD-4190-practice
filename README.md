# Dylan Riegert — Portfolio

Static portfolio site, published with GitHub Pages:
https://driegs17-alt.github.io/ARGD-4190-practice/

## Structure

```
index.html           Home
case-studies.html    Case study index (Milk, Conservation, Pike's Peak, Music)
stdwytk.html         Stuff They Don't Want You to Know — full case study
services.html
contact.html
works.html           Redirect from the old Works page

css/style.css        Shared styles for every page
css/stdwytk.css      Styles used only by stdwytk.html
js/main.js           Scroll-in animation (shared)

assets/img/<project>/   Web-sized images used by the pages
_source/                Full-resolution originals and the style guide (kept in the repo, not published)
```

## Adding images

Export a web copy (JPG, about 1600 px on the long edge, sRGB) into
`assets/img/<project>/` and reference it from the page. Keep the original
file in `_source/`.
