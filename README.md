# agera.js-modules

Public add-on files for legacy Agera.js, served via jsDelivr.

- **Status:** maintenance only. It is replaced by [`reform-society/agera`](https://github.com/reform-society/agera).
- **Owner:** Jens Harvard

## Contents

- `zip/`: postal-code lookup tables (`SE.js`, `NO.js`, `DK.js`, `FI.js`). Agera.js imports them at runtime to autofill the place name from a postal code.
- `dash/`: the old counter dashboard script (`dash.x.y.z.js`), kept for sites that still load it.

## Usage

```
https://cdn.jsdelivr.net/gh/reform-society/agera.js-modules@main/zip/SE.js
https://cdn.jsdelivr.net/gh/reform-society/agera.js-modules@main/dash/dash.0.6.0.js
```

Do not use the old `gh/ageraplattformen/js-modules` path. This repository must stay public for jsDelivr to serve it.
