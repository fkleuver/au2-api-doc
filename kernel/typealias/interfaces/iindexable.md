# IIndexable

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | IIndexable&lt;TBase, TValue, TKey&gt; |

# &#128712; Type Parameter(s)

| Type  | Constraint |
| ----- | ---------- |
| TBase | {}         |

| Type   | Constraint |
| ------ | ---------- |
| TValue | -          |

| Type | Constraint                         |
| ---- | ---------------------------------- |
| TKey | string &#124; number &#124; symbol |

# &#128712; Initializer

{ [K in TKey]: TValue } & TBase