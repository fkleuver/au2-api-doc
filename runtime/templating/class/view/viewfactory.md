| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IViewFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewfactory)&lt;T&gt; |

## &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**context**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/irendercontext)&lt;T&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**lifecycle**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ILifecycle](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ilifecycle) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**parts**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; &#124; undefined | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**maxCacheSize**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, static | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isCaching**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**cache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**cacheSize**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Method(s)

## setCacheSize

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**size**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number &#124; "*" | ✘  | ✘ | ✘ | - |

_**doNotOverrideIfAlreadySet**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |

## canReturnToCache

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**controller**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISyntheticView](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/isyntheticview)&lt;T&gt; | ✘  | ✘ | ✘ | - |

## tryReturnToCache

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**controller**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISyntheticView](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/isyntheticview)&lt;T&gt; | ✘  | ✘ | ✘ | - |

## create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ISyntheticView](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/isyntheticview)&lt;T&gt; |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) &#124; undefined | ✔  | ✘ | ✘ | - |

## resolve

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IViewFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewfactory)&lt;T&gt; |

**&#128966; Parameter(s)**

_**requestor**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

_**parts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; &#124; undefined | ✔  | ✘ | ✘ | - |