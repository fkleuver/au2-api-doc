# ObservedCollectionKindToType

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ObservedCollectionKindToType&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

T extends CollectionKind.array ? IObservedArray :
T extends CollectionKind.indexed ? IObservedArray :
T extends CollectionKind.map ? IObservedMap :
T extends CollectionKind.set ? IObservedSet :
T extends CollectionKind.keyed ? IObservedSet | IObservedMap :
never