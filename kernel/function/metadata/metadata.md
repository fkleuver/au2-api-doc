# &#128366; Summary

4.1.2 Reflect.metadata(metadataKey, metadataValue)
https:rbuckton.github.io/reflect-metadata/#reflect.metadata
A default metadata decorator factory that can be used on a class, class member, or parameter.

**Parameter(s)**

| Name          | Description                                                                                                                                             |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| metadataKey   |  The key for the metadata entry. If `metadataKey` is already defined for the target and target key, the metadataValue for that key will be overwritten. |
| metadataValue |  The value for the metadata entry.                                                                                                                      |

**Returns**

A decorator function.

# metadata

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| - | { (target: Function): void; (target: any, propertyKey: string &#124; symbol): void; } | ✘ | ✘  | ✔ |

## &#128966; Parameter(s)

_**metadataKey**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | any | ✘  | ✘ | ✘ | - |

_**metadataValue**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | any | ✘  | ✘ | ✘ | - |