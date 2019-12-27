# createElement

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | [RenderPlan](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/class/create-element/renderplan)&lt;T&gt; | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint              |
| ---- | ----------------------- |
| C    | Constructable&lt;{}&gt; |

## &#128966; Parameter(s)

_**dom**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**tagOrType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; C | ✘  | ✘ | ✘ | - |

_**props**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Record&lt;string, string &#124; IHydrateElementInstruction &#124; IHydrateTemplateController &#124; IHydrateLetElementInstruction &#124; IInterpolationInstruction &#124; IPropertyBindingInstruction &#124; IIteratorBindingInstruction &#124; ICallBindingInstruction &#124; IRefBindingInstruction &#124; ISetPropertyInstruction &#124; ILetBindingInstruction &#124; IHydrateAttributeInstruction &#124; ITextBindingInstruction &#124; IListenerBindingInstruction &#124; IAttributeBindingInstruction &#124; IStylePropertyBindingInstruction &#124; ISetAttributeInstruction &#124; ISetClassAttributeInstruction &#124; ISetStyleAttributeInstruction&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**children**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ArrayLike&lt;unknown&gt; &#124; undefined | ✔  | ✘ | ✘ | - |