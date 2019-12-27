# ReadonlyKeys

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | { [P in keyof T]-?: IfEquals&lt;{ [Q in P]: T[P]; }, { -readonly [Q in P]: T[P]; }, never, P&gt;; }[keyof T] |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

# &#128712; Initializer

{
[P in keyof T]-?: IfEquals<{ [Q in P]: T[P] }, { -readonly [Q in P]: T[P] }, never, P>
}[keyof T]