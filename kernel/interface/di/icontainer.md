# IContainer

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IServiceLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iservicelocator) |

# &#128712; Method(s)

## register

| Return Type                       |
|-----------------------------------|
| [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

**&#128966; Parameter(s)**

_**params**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| K    | Key        |

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## registerResolver

| Return Type                       |
|-----------------------------------|
| [IResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iresolver)&lt;T&gt; |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**resolver**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| K    | Key        |

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## registerTransformer

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**transformer**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| K    | Key        |

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## getResolver

| Return Type                       |
|-----------------------------------|
| [IResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iresolver)&lt;T&gt; &#124; null |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**autoRegister**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## getFactory

| Return Type                       |
|-----------------------------------|
| [IFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/ifactory)&lt;T&gt; &#124; null |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createChild

| Return Type                       |
|-----------------------------------|
| [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |