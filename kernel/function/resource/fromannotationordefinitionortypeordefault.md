# &#128366; Summary

The order in which the values are checked:
1. Annotations (usually set by decorators) have the highest priority; they override the definition as well as static properties on the type.
2. Definition properties (usually set by the customElement decorator object literal) come next. They override static properties on the type.
3. Static properties on the type come last. Note that this does not look up the prototype chain (bindables are an exception here, but we do that differently anyway)
4. The default property that is provided last. The function is only called if the default property is needed

# fromAnnotationOrDefinitionOrTypeOrDefault

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | Required&lt;TDef&gt;[K] | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                        |
| ---- | --------------------------------------------------------------------------------- |
| TDef | { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; } |

| Type | Constraint |
| ---- | ---------- |
| K    | keyof TDef |

## &#128966; Parameter(s)

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | K | ✘  | ✘ | ✘ | - |

_**def**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TDef | ✘  | ✘ | ✘ | - |

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**getDefault**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | () =&gt; Required&lt;TDef&gt;[K] | ✘  | ✘ | ✘ | - |