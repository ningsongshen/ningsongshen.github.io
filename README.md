# ningsongshen.github.io

Source for [ningsongshen.ca](https://ningsongshen.ca). No build step; GitHub Pages serves these files as-is.

- `404.html` is a copy of `index.html` with different ribbon text, no social metadata, and a single link home. Keep the CSS and script in sync when changing either.
- Fonts are [Inter](https://github.com/rsms/inter) (Latin) and [Noto Sans SC](https://github.com/notofonts/noto-cjk) (Chinese), both under the SIL Open Font License 1.1. They are subset to the glyphs the pages use and inlined as WOFF2, so new characters in the ribbons or links need a re-subset or they will fall back to system fonts.
