# &#128366; Summary

Retrieve the next ID in a sequence for a given string, starting with `1`.
Used by Aurelia to assign unique ID's to controllers and resources.
Aurelia will always prepend the context name with `au$`, so as long as you avoid
using that convention you should be safe from collisions.

# nextId

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | number | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**context**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |