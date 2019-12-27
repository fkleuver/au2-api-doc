# &#128366; Summary

Represents a DocumentFragment

# INodeSequence

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Property(ies)

## isMounted

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## isLinked

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## next

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;T&gt; &#124; undefined |

### &#128366; Summary

The nodes of this sequence.

## childNodes

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ArrayLike&lt;T&gt; |

## firstChild

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |

## lastChild

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |

# &#128712; Method(s)

### &#128366; Summary

Find all instruction targets in this sequence.

## findTargets

| Return Type                       |
|-----------------------------------|
| ArrayLike&lt;T&gt; |

### &#128366; Summary

Insert this sequence as a sibling before refNode

## insertBefore

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**refNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Append this sequence as a child to parent

## appendTo

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**parent**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Remove this sequence from the DOM.

## remove

| Return Type                       |
|-----------------------------------|
| void |

## addToLinked

| Return Type                       |
|-----------------------------------|
| void |

## unlink

| Return Type                       |
|-----------------------------------|
| void |

## link

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**next**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |