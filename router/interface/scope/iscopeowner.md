# IScopeOwner

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## connectedScope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) |

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) |

## owningScope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) |

## enabled

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## path

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; null |

## options

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IScopeOwnerOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/scope/iscopeowneroptions) |

## isViewport

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## isViewportScope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## isEmpty

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

# &#128712; Method(s)

## setNextContent

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**content**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## canLeave

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

## canEnter

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean &#124; [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[]&gt; |

## enter

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

## loadContent

| Return Type                       |
|-----------------------------------|
| Promise&lt;boolean&gt; |

## finalizeContentChange

| Return Type                       |
|-----------------------------------|
| void |

## abortContentChange

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## getRoutes

| Return Type                       |
|-----------------------------------|
| [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute)[] &#124; null |