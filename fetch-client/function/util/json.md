# &#128366; Summary

Serialize an object to JSON. Useful for easily creating JSON fetch request bodies.

**Parameter(s)**

| Name     | Description                                         |
| -------- | --------------------------------------------------- |
| body     |  The object to be serialized to JSON.               |
| replacer |  The JSON.stringify replacer used when serializing. |

**Returns**

A JSON string.

# json

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | string | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**body**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown | ✘  | ✘ | ✘ | - |

_**replacer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ((key: string, value: unknown) =&gt; unknown) &#124; undefined | ✔  | ✘ | ✘ | - |