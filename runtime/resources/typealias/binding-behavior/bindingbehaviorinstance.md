# BindingBehaviorInstance

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | BindingBehaviorInstance&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | {}         |

# &#128712; Initializer

{
bind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: T[]): void;
unbind(flags: LifecycleFlags, scope: IScope, binding: IBinding, ...args: T[]): void;
} & T