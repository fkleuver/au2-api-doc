# IOptionalPreprocessOptions

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## defaultShadowOptions

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | { mode: "open" &#124; "closed"; } &#124; undefined |

### &#128366; Summary

More details in ./preprocess-html-template.ts

## stringModuleWrap

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ((id: string) =&gt; string) &#124; undefined |

### &#128366; Summary

.css, .scss, .sass, .less, .styl

## cssExtensions

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

### &#128366; Summary

.js, .jsx, .ts, .tsx, .coffee

## jsExtensions

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

### &#128366; Summary

.html, .md, .pug, .haml, .jade, .slim, .slm

## templateExtensions

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string[] &#124; undefined |

### &#128366; Summary

When foo.js is paired by foo.md,
when foo.md is paried by foo.scss,
most bundlers require import original filename foo.md and foo.scss
instead of foo.html and foo.css.
But some bundlers (dumber) require import processed filename foo.html
and foo.css.

## useProcessedFilePairFilename

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

### &#128366; Summary

Whenn CSSModule is in use, stringModuleWrap is ignored.

## useCSSModule

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |