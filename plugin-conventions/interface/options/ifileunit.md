# IFileUnit

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

### &#128366; Summary

The path is used in sourceMap.

## path

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

### &#128366; Summary

The base path that file path is related to. Used for checking existence of the pair html.
We separated file path and base because file path will be written into source map.

## base

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## contents

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

### &#128366; Summary

For foo.js or foo.ts, this is foo.html or foo.md or foo.haml or foo.pug
For foo.html (or other templates), this is foo.css or foo.scss or foo.sass or foo.less or foo.styl

## filePair

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |