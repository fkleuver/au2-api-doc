# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## ValueConverter

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| ValueConverterKind | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; isType&lt;T&gt;(value: T): value is T extends Constructable&lt;{}&gt; ? ResourceType&lt;T, { toView(input: unknown, ...args: unknown[]): unknown; fromView?(input: unknown, ...args: unknown[]): unknown; }, {}, InstanceType&lt;T&gt;&gt; : never; define&lt;T extends Constructable&lt;{ toView(input: unknown, ...args: unknown[]): unknown; fromView?(input: unknown, ...args: unknown[]): unknown; }&gt;&gt;(nameOrDef: string &#124; { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; }, Type: T): ResourceType&lt;T, { toView(input: unknown, ...args: unknown[]): unknown; fromView?(input: unknown, ...args: unknown[]): unknown; }, {}, InstanceType&lt;T&gt;&gt;; getDefinition&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T): [ValueConverterDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/value-converter/valueconverterdefinition)&lt;T&gt;; annotate&lt;K extends "name" &#124; "aliases"&gt;(Type: Constructable&lt;{}&gt;, prop: K, value: { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; }[K]): void; getAnnotation&lt;K extends "name" &#124; "aliases"&gt;(Type: Constructable&lt;{}&gt;, prop: K): { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; }[K]; } | ✘  | ✘ |

### Value

Protocol.resource.keyFor('value-converter')

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
| T    | Constructable&lt;{ toView(input: unknown, ...args: unknown[]): unknown; fromView?(input: unknown, ...args: unknown[]): unknown; }&gt; |

## define

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | ResourceType&lt;T, { toView(input: unknown, ...args: unknown[]): unknown; fromView?(input: unknown, ...args: unknown[]): unknown; }, {}, InstanceType&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**nameOrDef**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; } | ✘  | ✘ | ✘ | - |

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
| - | ✘ | [ValueConverterDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/value-converter/valueconverterdefinition)&lt;T&gt; |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| K    | "name" &#124; "aliases" |

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
| - | { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; }[K] | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| K    | "name" &#124; "aliases" |

## getAnnotation

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | { readonly name: string; readonly aliases?: readonly string[] &#124; undefined; }[K] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**prop**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | K | ✘  | ✘ | ✘ | - |