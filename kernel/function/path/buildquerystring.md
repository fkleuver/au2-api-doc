# &#128366; Summary

Generate a query string from an object.

**Parameter(s)**

| Name        | Description                                          |
| ----------- | ---------------------------------------------------- |
| params      |  Object containing the keys and values to be used.   |
| traditional |  Boolean Use the old URI template standard (RFC6570) |

**Returns**

The generated query string, excluding leading '?'.

# buildQueryString

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | string | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IQueryParams](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/path/iqueryparams) &#124; undefined | ✔  | ✘ | ✘ | - |

_**traditional**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean &#124; undefined | ✔  | ✘ | ✘ | - |