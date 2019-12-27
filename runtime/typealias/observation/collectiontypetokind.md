# CollectionTypeToKind

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CollectionTypeToKind&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends unknown[] ? CollectionKind.array | CollectionKind.indexed :
T extends Set<unknown> ? CollectionKind.set | CollectionKind.keyed :
T extends Map<unknown, unknown> ? CollectionKind.map | CollectionKind.keyed :
never