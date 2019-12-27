# &#128366; Summary

A fully hydrated custom element controller.

# ICustomElementController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICompiledCustomElementController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icompiledcustomelementcontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                                              |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------- |
| C    | [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

### &#128366; Summary

**Inheritdoc**

## viewModel

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C |

### &#128366; Summary

**Inheritdoc**

## bindingContext

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C & { [x: string]: unknown; [x: number]: unknown; } |