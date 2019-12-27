# singleton

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | typeof singletonDecorator &#124; (T & RegisterSelf&lt;T&gt;) | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## &#128966; Parameter(s)

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | (T & Partial&lt;RegisterSelf&lt;T&gt;&gt;) &#124; undefined | ✔  | ✘ | ✘ | - |