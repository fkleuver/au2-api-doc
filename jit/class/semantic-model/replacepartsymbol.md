## &#128366; Summary

Wrapper for an element (with all of its attributes, regardless of the order in which they are declared)
that has a replace attribute on it.
This element will be lifted from the DOM just like a template controller.

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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**physicalNode**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| TElement &#124; null | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**parent**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| CustomElementSymbol&lt;TText, TElement, TMarker&gt; &#124; PlainElementSymbol&lt;TText, TElement, TMarker&gt; &#124; TemplateControllerSymbol&lt;TText, TElement, TMarker&gt; &#124; null | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**template**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| CustomElementSymbol&lt;TText, TElement, TMarker&gt; &#124; PlainElementSymbol&lt;TText, TElement, TMarker&gt; &#124; TemplateControllerSymbol&lt;TText, TElement, TMarker&gt; &#124; null | ✔  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flags**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |