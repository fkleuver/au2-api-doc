| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IViewLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/variable/view/iviewlocator) |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**modelInstanceToBoundComponent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**modelTypeToUnboundComponent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Method(s)

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iresolver)&lt;[IViewLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/variable/view/iviewlocator)&gt; |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                                                       |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | ClassInstance&lt;[ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt;&gt; |

## getViewComponentForObject

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | { new (...args: any[]): { viewModel: T; } & [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt; & { constructor: {}; }; readonly prototype: { viewModel: T; } & ICustomElementViewModel&lt;INode&gt; & { constructor: {}; }; } &#124; null |

**&#128966; Parameter(s)**

_**object**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T &#124; null &#124; undefined | ✘  | ✘ | ✘ | - |

_**viewNameOrSelector**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; ViewSelector &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                                                       |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | ClassInstance&lt;[ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt;&gt; |

## getOrCreateBoundComponent

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | { new (...args: any[]): { viewModel: T; } & [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt; & { constructor: {}; }; readonly prototype: { viewModel: T; } & ICustomElementViewModel&lt;INode&gt; & { constructor: {}; }; } |

**&#128966; Parameter(s)**

_**object**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**availableViews**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] | ✘  | ✘ | ✘ | - |

_**resolvedViewName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                                                                                                                                      |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | ClassInstance&lt;[ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;[INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode)&gt;&gt; |

## getOrCreateUnboundComponent

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | { new (...args: any[]): { viewModel: T; } & [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;[INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode)&gt; & { constructor: {}; }; readonly prototype: { viewModel: T; } & ICustomElementViewModel&lt;INode&gt; & { constructor: {}; }; } |

**&#128966; Parameter(s)**

_**object**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**availableViews**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] | ✘  | ✘ | ✘ | - |

_**resolvedViewName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## getViewName

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | string |

**&#128966; Parameter(s)**

_**views**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] | ✘  | ✘ | ✘ | - |

_**requestedName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; undefined | ✔  | ✘ | ✘ | - |

## getView

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt; |

**&#128966; Parameter(s)**

_**views**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |