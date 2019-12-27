## &#128366; Summary

Default implementation for `ITemplateFactory` for use in an HTML based runtime.

**Internal**

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [ITemplateElementFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/template-element-factory/itemplateelementfactory)&lt;INode&gt; |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IDOM | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt; | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**template**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Method(s)

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iresolver)&lt;[ITemplateElementFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/template-element-factory/itemplateelementfactory)&lt;INode&gt;&gt; |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## createTemplate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | HTMLTemplateElement |

**&#128966; Parameter(s)**

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Node | ✘  | ✘ | ✘ | - |