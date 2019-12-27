# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Views

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { name: string; has(value: object): boolean; get(value: object &#124; Constructable&lt;{}&gt;): readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[]; add&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T, partialDefinition: PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;): readonly CustomElementDefinition&lt;Constructable&lt;{}&gt;&gt;[]; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; has(value: object): boolean; get(value: object &#124; Constructable&lt;{}&gt;): readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[]; add&lt;T extends Constructable&lt;{}&gt;&gt;(Type: T, partialDefinition: PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;): readonly CustomElementDefinition&lt;Constructable&lt;{}&gt;&gt;[]; } | ✘  | ✘ |

### Value

Protocol.resource.keyFor('views')

### &#128712; Method(s)

## has

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | boolean |

**&#128966; Parameter(s)**

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | object | ✘  | ✘ | ✘ | - |

## get

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] |

**&#128966; Parameter(s)**

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | object &#124; Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## add

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt;[] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**partialDefinition**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |