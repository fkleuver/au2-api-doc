# IResourceKind

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Type Parameter(s)

| Type  | Constraint                                              |
| ----- | ------------------------------------------------------- |
| TType | ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt; |

| Type | Constraint                                                                                                                                                                                       |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| TDef | { readonly name: string; readonly Type: ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt;; readonly aliases?: readonly string[] &#124; undefined; register(container: IContainer): void; } |

# &#128712; Property(ies)

## name

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

# &#128712; Method(s)

## keyFrom

| Return Type                       |
|-----------------------------------|
| string |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |