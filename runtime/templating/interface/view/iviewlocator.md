# IViewLocator

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                                                       |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | ClassInstance&lt;[ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt;&gt; |

## getViewComponentForObject

| Return Type                       |
|-----------------------------------|
| { new (...args: any[]): { viewModel: T; } & [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt; & { constructor: {}; }; readonly prototype: { viewModel: T; } & ICustomElementViewModel&lt;INode&gt; & { constructor: {}; }; } &#124; null |

**&#128966; Parameter(s)**

_**object**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**viewNameOrSelector**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |