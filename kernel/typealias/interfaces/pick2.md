# &#128366; Summary

https:gist.github.com/staltz/368866ea6b8a167fbdac58cddf79c1bf

# Pick2

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | Pick2&lt;T, K1, K2&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

| Type | Constraint |
| ---- | ---------- |
| K1   | keyof T    |

| Type | Constraint  |
| ---- | ----------- |
| K2   | keyof T[K1] |

# &#128712; Initializer

{
[P1 in K1]: { [P2 in K2]: (T[K1])[P2] }
}