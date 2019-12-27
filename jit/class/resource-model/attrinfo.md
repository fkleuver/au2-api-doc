## &#128366; Summary

Pre-processed information about a custom attribute resource, optimized
for consumption by the template compiler.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isTemplateController**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

A lookup of the bindables of this attribute, indexed by the (pre-processed)
bindable names as they would be found in the attribute value.
Only applicable to multi attribute bindings (semicolon-separated).

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindables**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

The single or first bindable of this attribute, or a default 'value'
bindable if no bindables were defined on the attribute.
Only applicable to single attribute bindings (where the attribute value
contains no semicolons)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindable**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

## from

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [AttrInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/attrinfo) |

**&#128966; Parameter(s)**

_**def**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomAttributeDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-attribute/customattributedefinition)&lt;Constructable&lt;{}&gt;&gt; | ✘  | ✘ | ✘ | - |