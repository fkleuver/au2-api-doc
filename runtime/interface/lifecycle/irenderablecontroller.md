# &#128366; Summary

The base type for `ISyntheticView` and `ICustomElementController`.
Both of those types can:
- Have `bindings` and `controllers` which are populated during rendering (hence, 'Renderable').
- Have physical DOM nodes that can be mounted.

# IRenderableController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                    |
| ---- | ------------------------------------------------------------------------------------------------------------- |
| C    | [IViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

## vmKind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.customElement &#124; ViewModelKind.synthetic |

## bindings

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly [IBinding](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ibinding)[] &#124; undefined |

## controllers

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly IHydratedController&lt;T&gt;[] &#124; undefined |

# &#128712; Method(s)

## getTargetAccessor

| Return Type                       |
|-----------------------------------|
| [IBindingTargetAccessor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/ibindingtargetaccessor)&lt;any, string &#124; number &#124; symbol, unknown&gt; &#124; undefined |

**&#128966; Parameter(s)**

_**propertyName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## addBinding

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**binding**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## addController

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**controller**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |