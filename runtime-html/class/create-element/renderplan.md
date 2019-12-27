## &#128366; Summary

RenderPlan. Todo: describe goal of this class

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;T&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**node**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| T | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**instructions**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| HTMLTargetedInstruction[][] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dependencies**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Key[] | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**lazyDefinition**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

# &#128712; Get Accessor(s)

## definition

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## getContext

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/irendercontext)&lt;T&gt; |

**&#128966; Parameter(s)**

_**parentContainer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## createView

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ISyntheticView](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/isyntheticview)&lt;T&gt; |

**&#128966; Parameter(s)**

_**parentContainer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## getViewFactory

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IViewFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewfactory)&lt;T&gt; |

**&#128966; Parameter(s)**

_**parentContainer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |