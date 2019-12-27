# connectable

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | typeof connectableDecorator &#124; Class&lt;TProto & IConnectableBinding, TClass&gt; | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type   | Constraint |
| ------ | ---------- |
| TProto | -          |

| Type   | Constraint |
| ------ | ---------- |
| TClass | -          |

## &#128966; Parameter(s)

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Class&lt;TProto & Partial&lt;IConnectableBinding&gt; & IPartialConnectableBinding, TClass&gt; &#124; undefined | ✔  | ✘ | ✘ | - |