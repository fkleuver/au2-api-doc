# ResourceType

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | ResourceType&lt;TUserType, TResInstance, TResType, TUserInstance&gt; |

# &#128712; Type Parameter(s)

| Type      | Constraint              |
| --------- | ----------------------- |
| TUserType | Constructable&lt;{}&gt; |

| Type         | Constraint |
| ------------ | ---------- |
| TResInstance | {}         |

| Type     | Constraint |
| -------- | ---------- |
| TResType | {}         |

| Type          | Constraint                    |
| ------------- | ----------------------------- |
| TUserInstance | InstanceType&lt;TUserType&gt; |

# &#128712; Initializer

(
new (...args: any[]) => TResInstance & TUserInstance
) & {
readonly aliases?: readonly string[];
} & TResType & TUserType