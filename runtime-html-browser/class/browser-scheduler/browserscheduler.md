| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IClock | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**clock**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IClock](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/iclock) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IDOM | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HTMLDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/class/dom/htmldom) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**taskQueue**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flush**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Method(s)

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | void |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## getTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [TaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/scheduler/taskqueue) |

**&#128966; Parameter(s)**

_**priority**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [TaskQueuePriority](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/scheduler/taskqueuepriority) | ✘  | ✘ | ✘ | - |

## yield

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**priority**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [TaskQueuePriority](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/scheduler/taskqueuepriority) | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Task](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/scheduler/task)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskTargetOptions &#124; undefined | ✔  | ✘ | ✘ | - |

## getMicroTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getRenderTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getMacroTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getPostRenderTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

## getIdleTaskQueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itaskqueue) |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldMicroTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldRenderTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldMacroTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldPostRenderTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldIdleTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;void&gt; |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## yieldAll

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, async | ✘ | Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**repeat**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number | ✔  | ✘ | ✘ | 1 |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueMicroTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskOptions &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueRenderTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskOptions &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueMacroTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskOptions &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queuePostRenderTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskOptions &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## queueIdleTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ITask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/scheduler/itask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TaskCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**opts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | QueueTaskOptions &#124; undefined | ✔  | ✘ | ✘ | - |

## requestFlush

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**taskQueue**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [TaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/scheduler/taskqueue) | ✘  | ✘ | ✘ | - |

## cancelFlush

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**taskQueue**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [TaskQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/scheduler/taskqueue) | ✘  | ✘ | ✘ | - |