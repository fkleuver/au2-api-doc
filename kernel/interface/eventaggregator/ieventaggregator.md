# IEventAggregator

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## publish

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**channelOrInstance**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**data**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## subscribe

| Return Type                       |
|-----------------------------------|
| [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

**&#128966; Parameter(s)**

_**channelOrType**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**callback**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## subscribeOnce

| Return Type                       |
|-----------------------------------|
| [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

**&#128966; Parameter(s)**

_**channelOrType**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**callback**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |