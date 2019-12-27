# LengthPropertyName

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | LengthPropertyName&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends unknown[] ? 'length' :
T extends Set<unknown> ? 'size' :
T extends Map<unknown, unknown> ? 'size' :
never