| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IInstructionRenderer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/renderer/iinstructionrenderer)&lt;string&gt; |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| inject | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| IObserverLocator  |

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| instructionRenderer | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| 'au'  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**observerLocator**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IObserverLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/observer-locator/iobserverlocator) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**observerLocator**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Method(s)

## render

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) | ✘  | ✘ | ✘ | - |

_**context**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

_**controller**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ICustomElementController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementcontroller)&lt;[AuNode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/aunode), ICustomElementViewModel&lt;AuNode&gt;&gt; | ✘  | ✘ | ✘ | - |

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AuNode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/aunode) | ✘  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AuTextInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/autextinstruction) | ✘  | ✘ | ✘ | - |