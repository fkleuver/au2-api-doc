| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IElementProjector](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/interface/custom-element/ielementprojector)&lt;INode&gt; |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$controller**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ICustomElementController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementcontroller)&lt;[AuNode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/aunode), ICustomElementViewModel&lt;AuNode&gt;&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**host**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| CustomElementHost&lt;[AuNode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/aunode)&gt; | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**host**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Get Accessor(s)

## children

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## subscribeToChildrenChange

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | () =&gt; void | ✘  | ✘ | ✘ | - |

## provideEncapsulationSource

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [AuNode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/au-dom/aunode) |

## project

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**nodes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;INode&gt; | ✘  | ✘ | ✘ | - |

## take

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**nodes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;INode&gt; | ✘  | ✘ | ✘ | - |