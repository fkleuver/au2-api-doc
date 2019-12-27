# ITaskQueue

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## priority

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [TaskQueuePriority](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/scheduler/taskqueuepriority) |

# &#128712; Method(s)

## flush

| Return Type                       |
|-----------------------------------|
| void |

## cancel

| Return Type                       |
|-----------------------------------|
| void |

## yield

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueTask

| Return Type                       |
|-----------------------------------|
| [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## take

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**task**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## remove

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**task**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |