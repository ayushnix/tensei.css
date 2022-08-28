# tensei.css (転生, reincarnation)

tensei.css is a lightweight classless CSS framework that is meant to be used on static websites with
a strong focus on text, readability, accessibility, and reducing distractions.

## Web Browser Compatibility

There is no intent or desire to maintain compatibility with any version of Internet Explorer. This
project is intended to be used on the following browser engines and web browsers:

- Gecko: Firefox Stable and ESR
- Blink: Chromium Stable, qt5-webengine browsers like qutebrowser
- WebKit: Safari Desktop, Safari iOS, webkit2gtk browsers like luakit and Epiphany

## TODO

- switch to [CSS logical properties][1] whenever they get their own [shorthand logical syntax][2]
  and browser wide support for them becomes available
- consider implementing a hover tooltip for the `<abbr>` element on mobile by creating a lightbox
  using :target, `<dfn>`, and the [doc-glossary role][3] in a `<section>`, maybe `<dialog>` would be
  helpful?

[1]: https://caniuse.com/css-logical-props
[2]: https://github.com/w3c/csswg-drafts/issues/1282
[3]: https://w3c.github.io/dpub-aria/#doc-glossary
