# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Bindable

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { name: string; keyFrom(name: string): string; from(...bindableLists: readonly (readonly string[] &#124; Record&lt;string, Partial[BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; &#124; BindableDefinition &#124; undefined)[]): Record&lt;string, BindableDefinition&gt;; for(Type: Constructable&lt;{}&gt;): BFluent; getAll(Type: Constructable&lt;{}&gt;): readonly BindableDefinition[]; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### name

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { name: string; keyFrom(name: string): string; from(...bindableLists: readonly (readonly string[] &#124; Record&lt;string, Partial[BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; &#124; BindableDefinition &#124; undefined)[]): Record&lt;string, BindableDefinition&gt;; for(Type: Constructable&lt;{}&gt;): BFluent; getAll(Type: Constructable&lt;{}&gt;): readonly BindableDefinition[]; } | ✘  | ✘ |

### Value

Protocol.annotation.keyFor('bindable')

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
| - | ✘ | Record&lt;string, [BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; |

**&#128966; Parameter(s)**

_**bindableLists**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | readonly (readonly string[] &#124; Record&lt;string, Partial[BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; &#124; BindableDefinition &#124; undefined)[] | ✔  | ✔ | ✘ | - |

## for

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | BFluent |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

## getAll

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | readonly [BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)[] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; | ✘  | ✘ | ✘ | - |