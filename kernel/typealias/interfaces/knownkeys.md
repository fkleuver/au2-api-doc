# KnownKeys

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | KnownKeys&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

{
[K in keyof T]: string extends K ? never : number extends K ? never : K
} extends {[_ in keyof T]: infer U} ? U : never