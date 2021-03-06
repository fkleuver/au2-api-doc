| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IAutoProcessingQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iautoprocessingqueue)&lt;[IController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icontroller)&lt;INode, IViewModel&lt;INode&gt;&gt;&gt; |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| ILifecycle | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**lifecycle**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ILifecycle](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ilifecycle) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**depth**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**head**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**tail**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

## begin

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## end

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) &#124; undefined | ✔  | ✘ | ✘ | - |

## inline

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**fn**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | () =&gt; void | ✘  | ✘ | ✘ | - |

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) &#124; undefined | ✔  | ✘ | ✘ | - |

## add

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**controller**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IComponentController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icomponentcontroller)&lt;INode, IViewModel&lt;INode&gt;&gt; | ✘  | ✘ | ✘ | - |

## remove

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**controller**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IComponentController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icomponentcontroller)&lt;INode, IViewModel&lt;INode&gt;&gt; | ✘  | ✘ | ✘ | - |

## process

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) | ✘  | ✘ | ✘ | - |