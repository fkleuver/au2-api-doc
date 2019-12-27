# IStoredNavigatorEntry

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## instruction

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] |

## fullStateInstruction

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] |

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) &#124; null &#124; undefined |

## index

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | number &#124; undefined |

### &#128366; Summary

Index might change to not require first === 0, firstEntry should be reliable

## firstEntry

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

## route

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute) &#124; undefined |

## path

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## title

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## query

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## parameters

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | Record&lt;string, unknown&gt; &#124; undefined |

## data

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | Record&lt;string, unknown&gt; &#124; undefined |