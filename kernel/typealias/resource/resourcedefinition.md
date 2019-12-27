# ResourceDefinition

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ResourceDefinition&lt;TUserType, TResInstance, TDef, TResType, TUserInstance&gt; |

# &#128712; Type Parameter(s)

| Type      | Constraint              |
| --------- | ----------------------- |
| TUserType | Constructable&lt;{}&gt; |

| Type         | Constraint |
| ------------ | ---------- |
| TResInstance | {}         |

| Type | Constraint |
| ---- | ---------- |
| TDef | {}         |

| Type     | Constraint |
| -------- | ---------- |
| TResType | {}         |

| Type          | Constraint                    |
| ------------- | ----------------------------- |
| TUserInstance | InstanceType&lt;TUserType&gt; |

# &#128712; Initializer

{
readonly name: string;
readonly Type: ResourceType<TUserType, TResInstance, TResType, TUserInstance>;
readonly aliases?: readonly string[];
register(container: IContainer): void;
} & TDef