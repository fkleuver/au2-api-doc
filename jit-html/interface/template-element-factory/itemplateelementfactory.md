# &#128366; Summary

Utility that creates a `HTMLTemplateElement` out of string markup or an existing DOM node.
It is idempotent in the sense that passing in an existing template element will simply return that template element,
so it is always safe to pass in a node without causing unnecessary DOM parsing or template creation.

# ITemplateElementFactory

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Type Parameter(s)

| Type  | Constraint                                                                           |
| ----- | ------------------------------------------------------------------------------------ |
| TNode | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Method(s)

### &#128366; Summary

Create a `HTMLTemplateElement` from a provided html string.

**Parameter(s)**

| Name   | Description                                                                  |
| ------ | ---------------------------------------------------------------------------- |
| markup |  A raw html string that may or may not be wrapped in `<template></template>` |

## createTemplate

| Return Type                       |
|-----------------------------------|
| TNode |

**&#128966; Parameter(s)**

_**markup**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Create a `HTMLTemplateElement` from a provided DOM node. If the node is already a template, it
will be returned as-is (and removed from the DOM).

**Parameter(s)**

| Name | Description                                                           |
| ---- | --------------------------------------------------------------------- |
| node |  A DOM node that may or may not be wrapped in `<template></template>` |

## createTemplate

| Return Type                       |
|-----------------------------------|
| TNode |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Create a `HTMLTemplateElement` from a provided DOM node or html string.

**Parameter(s)**

| Name  | Description                                                                              |
| ----- | ---------------------------------------------------------------------------------------- |
| input |  A DOM node or raw html string that may or may not be wrapped in `<template></template>` |

## createTemplate

| Return Type                       |
|-----------------------------------|
| TNode |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createTemplate

| Return Type                       |
|-----------------------------------|
| TNode |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |