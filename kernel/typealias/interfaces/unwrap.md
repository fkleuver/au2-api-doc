# Unwrap

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | Unwrap&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends (infer U)[] ? U :
T extends (...args: unknown[]) => infer U ? U :
T extends Promise<infer U> ? U :
T