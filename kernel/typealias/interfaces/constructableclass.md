# &#128366; Summary

For resources, we want the 'constructor' property to remain on the instance type but we need to do that
with a separate type from Class, since that one is used for other things where this constructor property
would break the typings.
So, in lack of a better name.. we probably need to clean this up, but this is how it works for now.

# ConstructableClass

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ConstructableClass&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

| Type | Constraint |
| ---- | ---------- |
| C    | -          |

# &#128712; Initializer

C & {
readonly prototype: T & { constructor: C };
new(...args: any[]): T & { constructor: C };
}