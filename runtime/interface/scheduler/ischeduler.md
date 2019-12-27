# IScheduler

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Method(s)

## getTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

**&#128966; Parameter(s)**

_**priority**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## yield

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**priority**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

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

## getMicroTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getRenderTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getMacroTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getPostRenderTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getIdleTaskQueue

| Return Type                       |
|-----------------------------------|
| [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## yieldMicroTask

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## yieldRenderTask

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## yieldMacroTask

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## yieldPostRenderTask

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## yieldIdleTask

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## yieldAll

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**repeat**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueMicroTask

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

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueRenderTask

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

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueMacroTask

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

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queuePostRenderTask

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

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueIdleTask

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