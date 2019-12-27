| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| valueConverter | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| 'view'  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IViewLocator | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**viewLocator**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IViewLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/variable/view/iviewlocator) | ✘  | ✘ | ✔ |

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| T    | [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt; |

## toView

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