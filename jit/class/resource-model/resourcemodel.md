## &#128366; Summary

A pre-processed piece of information about declared custom elements, attributes and
binding commands, optimized for consumption by the template compiler.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**container**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**elementLookup**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**attributeLookup**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**commandLookup**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**container**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**resourceResolvers**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**rootResourceResolvers**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Method(s)

## getOrCreate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [ResourceModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/resourcemodel) |

**&#128966; Parameter(s)**

_**context**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Retrieve information about a custom element resource.

**Parameter(s)**

The original DOM element.

**Returns**

The resource information if the element exists, or `null` if it does not exist.

## getElementInfo

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ElementInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/elementinfo) &#124; null |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Retrieve information about a custom attribute resource.

**Parameter(s)**

| Name   | Description              |
| ------ | ------------------------ |
| syntax |  The parsed `AttrSyntax` |

**Returns**

The resource information if the attribute exists, or `null` if it does not exist.

## getAttributeInfo

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [AttrInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/attrinfo) &#124; null |

**&#128966; Parameter(s)**

_**syntax**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Retrieve a binding command resource.

**Parameter(s)**

The parsed `AttrSyntax`

**Returns**

An instance of the command if it exists, or `null` if it does not exist.

## getBindingCommand

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } &#124; null |

**&#128966; Parameter(s)**

_**syntax**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ | - |

_**optional**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type  | Constraint                                              |
| ----- | ------------------------------------------------------- |
| TType | ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt; |

| Type | Constraint                                                                                                                                                                                                                                                                         |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TDef | { readonly name: string; readonly Type: ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt;; readonly aliases?: readonly string[] &#124; undefined; register(container: [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer)): void; } |

## find

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | TDef &#124; null |

**&#128966; Parameter(s)**

_**kind**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IResourceKind](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/resource/iresourcekind)&lt;TType, TDef&gt; | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type  | Constraint                                              |
| ----- | ------------------------------------------------------- |
| TType | ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt; |

| Type | Constraint                                                                                                                                                                                                                                                                         |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| TDef | { readonly name: string; readonly Type: ResourceType&lt;Constructable&lt;{}&gt;, {}, {}, {}&gt;; readonly aliases?: readonly string[] &#124; undefined; register(container: [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer)): void; } |

## create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | InstanceType&lt;TType&gt; &#124; null |

**&#128966; Parameter(s)**

_**kind**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IResourceKind](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/resource/iresourcekind)&lt;TType, TDef&gt; | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |