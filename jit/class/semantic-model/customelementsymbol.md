## &#128366; Summary

A html element that is associated with a registered resource either via its (lowerCase) `nodeName`
or the value of its `as-element` attribute.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Type Parameter(s)

| Type  | Constraint                                                                           |
| ----- | ------------------------------------------------------------------------------------ |
| TText | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type     | Constraint                                                                           |
| -------- | ------------------------------------------------------------------------------------ |
| TElement | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type    | Constraint                                                                           |
| ------- | ------------------------------------------------------------------------------------ |
| TMarker | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**physicalNode**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| TElement | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**info**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ElementInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/elementinfo) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**res**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindables**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Record&lt;string, [BindableInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/bindableinfo) &#124; undefined&gt; | ✔  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flags**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isTarget**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**templateController**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isContainerless**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**marker**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_customAttributes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_plainAttributes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_bindings**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_childNodes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_parts**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Get Accessor(s)

## customAttributes

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## plainAttributes

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## bindings

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## childNodes

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## parts

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |