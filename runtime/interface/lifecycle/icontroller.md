# &#128366; Summary

The base type for all controller types.
Every controller, regardless of their type and state, will have at least the properties/methods in this interface.

# IController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                    |
| ---- | ------------------------------------------------------------------------------------------------------------- |
| C    | [IViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

## flags

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) |

## state

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [State](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/state) |

## parent

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ISyntheticView&lt;T&gt; &#124; ICustomElementController&lt;T, ICustomElementViewModel&lt;T&gt;&gt; &#124; ICustomAttributeController&lt;T, ICustomAttributeViewModel&lt;T&gt;&gt; &#124; undefined |

## lifecycle

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILifecycle](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ilifecycle) |

## hooks

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition) |

## vmKind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ViewModelKind](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/lifecycle/viewmodelkind) |

## part

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; undefined |

# &#128712; Method(s)

## bind

| Return Type                       |
|-----------------------------------|
| [ILifecycleTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle-task/ilifecycletask)&lt;unknown&gt; |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**partName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## unbind

| Return Type                       |
|-----------------------------------|
| [ILifecycleTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle-task/ilifecycletask)&lt;unknown&gt; |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## attach

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## detach

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## cache

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |