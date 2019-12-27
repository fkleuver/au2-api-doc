# Diff

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ({ [P in T]: P; } & { [P in U]: never; } & { [x: string]: never; })[T] |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | string     |

| Type | Constraint |
| ---- | ---------- |
| U    | string     |

# &#128712; Initializer

({[P in T]: P } & {[P in U]: never } & { [x: string]: never })[T]