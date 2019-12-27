# BindingCommandInstance

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | BindingCommandInstance&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | {}         |

# &#128712; Initializer

{
bindingType: BindingType;
compile(binding: PlainAttributeSymbol | BindingSymbol): ITargetedInstruction;
} & T