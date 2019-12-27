# OptionalKnownKeys

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | OptionalKnownKeys&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

{
[K in keyof T]: string extends K ? never : number extends K ? never : {} extends Pick<T, K> ? K : never
} extends { [_ in keyof T]: infer U } ? ({} extends U ? never : U) : never