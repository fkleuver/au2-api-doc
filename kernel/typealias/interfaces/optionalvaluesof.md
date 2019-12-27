# OptionalValuesOf

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | OptionalValuesOf&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends { [_ in keyof T]: infer U } ? U : never