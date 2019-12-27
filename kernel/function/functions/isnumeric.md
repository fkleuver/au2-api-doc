# &#128366; Summary

Efficiently determine whether the provided property key is numeric
(and thus could be an array indexer) or not.
Always returns true for values of type `'number'`.
Otherwise, only returns true for strings that consist only of positive integers.
Results are cached.

# isNumeric

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | boolean | ✘ | ✘  | ✔ |

# &#128712; Type Guard

| On                             |
|--------------------------------|
| string &#124; number |

## &#128966; Parameter(s)

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown | ✘  | ✘ | ✘ | - |