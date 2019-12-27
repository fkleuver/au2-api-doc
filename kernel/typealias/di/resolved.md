# Resolved

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | Resolved&lt;K&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| K    | -          |

# &#128712; Initializer

(
K extends InterfaceSymbol<infer T>
? T
: K extends Constructable
? InstanceType<K>
: K extends IResolverLike<any, infer T1>
? T1 extends Constructable
? InstanceType<T1>
: T1
: K
)