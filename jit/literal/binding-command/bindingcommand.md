# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## BindingCommand

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| BindingCommandKind | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends Constructable&lt;{}&gt; ? ResourceType&lt;T, { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; }, PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; : never; define&lt;T extends Constructable&lt;{ bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; }&gt;&gt;(nameOrDef: string &#124; PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;, Type: T): T & (new (...args: any[]) =&gt; { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } & InstanceType&lt;T&gt;) & { readonly aliases?: readonly string[] &#124; undefined; } & { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; } & { readonly type?: string &#124; null &#124; undefined; }; getDefinition&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T): [BindingCommandDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/binding-command/bindingcommanddefinition)&lt;T&gt;; annotate&lt;K extends "name" &#124; "aliases" &#124; "type"&gt;(Type: Constructable&lt;{}&gt;, prop: K, value: PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;[K]): void; getAnnotation&lt;K extends "name" &#124; "aliases" &#124; "type"&gt;(Type: Constructable&lt;{}&gt;, prop: K): PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;[K]; } | ✘  | ✘ |

### Value

Protocol.resource.keyFor('binding-command')

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

| Type | Constraint                                                                                                                            |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------- |
| T    | Constructable&lt;{ bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; }&gt; |

## define

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | T & (new (...args: any[]) =&gt; { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } & InstanceType&lt;T&gt;) & { readonly aliases?: readonly string[] &#124; undefined; } & { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; } & { readonly type?: string &#124; null &#124; undefined; } |

**&#128966; Parameter(s)**

_**nameOrDef**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

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
| - | ✘ | [BindingCommandDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/binding-command/bindingcommanddefinition)&lt;T&gt; |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| K    | "name" &#124; "aliases" &#124; "type" |

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
| - | PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;[K] | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| K    | "name" &#124; "aliases" &#124; "type" |

## getAnnotation

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | PartialResourceDefinition&lt;{ readonly type?: string &#124; null &#124; undefined; }&gt;[K] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**prop**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | K | ✘  | ✘ | ✘ | - |