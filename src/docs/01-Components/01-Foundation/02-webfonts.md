The YouSee brand font is LTF Etica and it's loaded using the `@font-face` strategy. It comes in four different weights:
- light (200)
- regular (400)
- semibold (600)
- bold (800)

```
@font-face {
  font-family: 'Etica';
  src: url('//s.c.dk/fonts/lft_etica_light-webfont.woff2') format('woff2'), url('//s.c.dk/fonts/lft_etica_light-webfont.woff') format('woff');
  font-weight: 200;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Etica';
  src: url('//s.c.dk/fonts/lft_etica_reg-webfont.woff2') format('woff2'), url('//s.c.dk/fonts/lft_etica_reg-webfont.woff') format('woff');
  font-weight: 400;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Etica';
  src: url('//s.c.dk/fonts/lft_etica_semibold-webfont.woff2') format('woff2'), url('//s.c.dk/fonts/lft_etica_semibold-webfont.woff') format('woff');
  font-weight: 600;
  font-style: normal;
  font-display: swap;
}

@font-face {
  font-family: 'Etica';
  src: url('//s.c.dk/fonts/lft_etica_bold-webfont.woff2') format('woff2'), url('//s.c.dk/fonts/lft_etica_bold-webfont.woff') format('woff');
  font-weight: 700;
  font-style: normal;
  font-display: swap;
}
```