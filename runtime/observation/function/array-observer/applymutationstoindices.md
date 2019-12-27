# &#128366; Summary

Applies offsets to the non-negative indices in the IndexMap
based on added and deleted items relative to those indices.
e.g. turn `[-2, 0, 1]` into `[-2, 1, 2]`, allowing the values at the indices to be
used for sorting/reordering items if needed

# applyMutationsToIndices

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | void | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**indexMap**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | IndexMap | ✘  | ✘ | ✘ | - |