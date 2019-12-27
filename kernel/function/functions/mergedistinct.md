# &#128366; Summary

Efficiently merge and deduplicate the (primitive) values in two arrays.
Does not deduplicate existing values in the first array.
Guards against null or undefined arrays.
Returns `PLATFORM.emptyArray` if both arrays are either `null`, `undefined` or `PLATFORM.emptyArray`

**Parameter(s)**

| Name  | Description                                                                       |
| ----- | --------------------------------------------------------------------------------- |
| slice |  If `true`, always returns a new array copy (unless neither array is/has a value) |

# mergeDistinct

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | T[] | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## &#128966; Parameter(s)

_**arr1**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T[] &#124; readonly T[] &#124; null &#124; undefined | ✘  | ✘ | ✘ | - |

_**arr2**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T[] &#124; readonly T[] &#124; null &#124; undefined | ✘  | ✘ | ✘ | - |

_**slice**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |