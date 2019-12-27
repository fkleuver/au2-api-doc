# BindingCommandType

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ResourceType&lt;T, { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; }, PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

# &#128712; Initializer

ResourceType<T, BindingCommandInstance, PartialBindingCommandDefinition>