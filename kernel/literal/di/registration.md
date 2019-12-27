# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Registration

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { instance&lt;T&gt;(key: Key, value: T): [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;T&gt;; singleton&lt;T extends Constructable&lt;{}&gt;&gt;(key: Key, value: T): IRegistration&lt;InstanceType&lt;T&gt;&gt;; transient&lt;T extends Constructable&lt;{}&gt;&gt;(key: Key, value: T): IRegistration&lt;InstanceType&lt;T&gt;&gt;; callback&lt;T&gt;(key: Key, callback: ResolveCallback&lt;T&gt;): IRegistration&lt;Resolved&lt;T&gt;&gt;; alias&lt;T&gt;(originalKey: T, aliasKey: Key): IRegistration&lt;Resolved&lt;T&gt;&gt;; defer(key: Key, ...params: unknown[]): [IRegistry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistry); } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## instance

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;T&gt; |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## singleton

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;InstanceType&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## transient

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;InstanceType&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## callback

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;Resolved&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ResolveCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## alias

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistration](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistration)&lt;Resolved&lt;T&gt;&gt; |

**&#128966; Parameter(s)**

_**originalKey**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**aliasKey**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

## defer

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IRegistry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistry) |

**&#128966; Parameter(s)**

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key | ✘  | ✘ | ✘ | - |

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown[] | ✔  | ✔ | ✘ | - |