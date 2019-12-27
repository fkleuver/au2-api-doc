# &#128366; Summary

The order in which the values are checked:
1. Definition properties.
2. The default property that is provided last. The function is only called if the default property is needed

# fromDefinitionOrDefault

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

_**getDefault**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | () =&gt; Required&lt;TDef&gt;[K] | ✘  | ✘ | ✘ | - |