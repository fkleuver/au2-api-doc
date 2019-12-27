# &#128366; Summary

https:github.com/Microsoft/TypeScript/issues/14829#issuecomment-322267089

# NoInfer

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | NoInfer&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T & { [K in keyof T]: T[K] }