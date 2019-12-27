# IRouteableComponent

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Property(ies)

## reentryBehavior

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [ReentryBehavior](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/enum/interfaces/reentrybehavior) &#124; undefined |

# &#128712; Method(s)

## canEnter

| Return Type                       |
|-----------------------------------|
| string &#124; boolean &#124; [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] &#124; Promise&lt;string &#124; boolean &#124; ViewportInstruction[]&gt; |

**&#128966; Parameter(s)**

_**parameters**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**nextInstruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## enter

| Return Type                       |
|-----------------------------------|
| void &#124; Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**parameters**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**nextInstruction**_

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
| boolean &#124; Promise&lt;boolean&gt; |

**&#128966; Parameter(s)**

_**nextInstruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## leave

| Return Type                       |
|-----------------------------------|
| void &#124; Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**nextInstruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |