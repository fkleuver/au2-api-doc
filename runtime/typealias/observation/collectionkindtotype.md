# CollectionKindToType

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | CollectionKindToType&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends CollectionKind.array ? unknown[] :
T extends CollectionKind.indexed ? unknown[] :
T extends CollectionKind.map ? Map<unknown, unknown> :
T extends CollectionKind.set ? Set<unknown> :
T extends CollectionKind.keyed ? Set<unknown> | Map<unknown, unknown> :
never