| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IBinding](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ibinding) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**observerLocator**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IObserverLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/observer-locator/iobserverlocator) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**interpolation**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IInterpolationExpression](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/ast/iinterpolationexpression) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**target**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| object | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**targetProperty**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**mode**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [BindingMode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingmode) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**locator**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IServiceLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iservicelocator) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**interceptor**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$state**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$scope**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**part**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**parts**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

## $bind

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) | ✘  | ✘ | ✘ | - |

_**scope**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/iscope) | ✘  | ✘ | ✘ | - |

_**part**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; undefined | ✔  | ✘ | ✘ | - |

## $unbind

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) | ✘  | ✘ | ✘ | - |