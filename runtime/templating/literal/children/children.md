# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Children

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { name: string; keyFrom(name: string): string; from(...childrenObserverLists: readonly (readonly string[] &#124; Record&lt;string, Partial[ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;&gt; &#124; ChildrenDefinition&lt;INode&gt; &#124; undefined)[]): Record&lt;string, ChildrenDefinition&lt;INode&gt;&gt;; getAll(Type: Constructable&lt;{}&gt;): readonly ChildrenDefinition&lt;INode&gt;[]; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; from(...childrenObserverLists: readonly (readonly string[] &#124; Record&lt;string, Partial[ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;&gt; &#124; ChildrenDefinition&lt;INode&gt; &#124; undefined)[]): Record&lt;string, ChildrenDefinition&lt;INode&gt;&gt;; getAll(Type: Constructable&lt;{}&gt;): readonly ChildrenDefinition&lt;INode&gt;[]; } | ✘  | ✘ |

### Value

Protocol.annotation.keyFor('children-observer')

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

## from

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | Record&lt;string, [ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;&gt; |

**&#128966; Parameter(s)**

_**childrenObserverLists**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly (readonly string[] &#124; Record&lt;string, Partial[ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;&gt; &#124; ChildrenDefinition&lt;INode&gt; &#124; undefined)[] | ✔  | ✔ | ✘ | - |

## getAll

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly [ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;[] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |