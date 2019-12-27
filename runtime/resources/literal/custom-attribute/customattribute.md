# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## CustomAttribute

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| CustomAttributeKind | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends Constructable&lt;{}&gt; ? ResourceType&lt;T, [ICustomAttributeViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributeviewmodel)&lt;[INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode)&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; : never; for&lt;T extends INode = INode, C extends ICustomAttributeViewModel&lt;T&gt; = ICustomAttributeViewModel&lt;T&gt;&gt;(node: T, name: string): [ICustomAttributeController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributecontroller)&lt;T, C&gt; &#124; undefined; define&lt;T extends Constructable&lt;{}&gt;&gt;(nameOrDef: string &#124; PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, Type: T): ResourceType&lt;T, ICustomAttributeViewModel&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt;; getDefinition&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T): [CustomAttributeDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-attribute/customattributedefinition)&lt;T&gt;; annotate&lt;K extends "isTemplateController" &#124; "name" &#124; "aliases" &#124; "defaultBindingMode" &#124; "bindables" &#124; "strategy" &#124; "hooks"&gt;(Type: Constructable&lt;{}&gt;, prop: K, value: PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;[K]): void; getAnnotation&lt;K extends "isTemplateController" &#124; "name" &#124; "aliases" &#124; "defaultBindingMode" &#124; "bindables" &#124; "strategy" &#124; "hooks"&gt;(Type: Constructable&lt;{}&gt;, prop: K): PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;[K]; } | ✘  | ✘ |

### Value

Protocol.resource.keyFor('custom-attribute')

### &#128712; Method(s)

## keyFrom

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | string |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## isType

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | boolean |

**&#128966; Parameter(s)**

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |
| Type | Constraint                                                                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| C    | [ICustomAttributeViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributeviewmodel)&lt;T&gt; |

## for

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [ICustomAttributeController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributecontroller)&lt;T, C&gt; &#124; undefined |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## define

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | ResourceType&lt;T, ICustomAttributeViewModel&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**nameOrDef**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## getDefinition

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [CustomAttributeDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-attribute/customattributedefinition)&lt;T&gt; |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                            |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------- |
| K    | "isTemplateController" &#124; "name" &#124; "aliases" &#124; "defaultBindingMode" &#124; "bindables" &#124; "strategy" &#124; "hooks" |

## annotate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**prop**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | K | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;[K] | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                                                                                                                            |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------- |
| K    | "isTemplateController" &#124; "name" &#124; "aliases" &#124; "defaultBindingMode" &#124; "bindables" &#124; "strategy" &#124; "hooks" |

## getAnnotation

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;[K] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**prop**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | K | ✘  | ✘ | ✘ | - |