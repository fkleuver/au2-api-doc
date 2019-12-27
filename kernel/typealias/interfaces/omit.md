# Omit

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | Omit&lt;T, K&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

| Type | Constraint |
| ---- | ---------- |
| K    | keyof T    |

# &#128712; Initializer

T extends {} ? Pick<T, Exclude<keyof T, K>> : never