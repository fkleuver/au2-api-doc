## &#128366; Summary

A first-in-first-out task queue that only processes the next queued item
when the current one has been resolved or rejected. If a callback function
is specified, it receives the queued items as tasks one at a time. If no
callback is specified, the tasks themselves are either executed (if a
function) or the execute method in them are run. The executed function
should resolve or reject the task when processing is done.
Enqueued items' tasks can be awaited. Enqueued items can specify an
(arbitrary) execution cost and the queue can be set up (activated) to
only process a specific amount of execution cost per RAF/tick.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**callback**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| ((task: [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt;) =&gt; void) &#124; undefined | ✔  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pending**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**processing**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**allowedExecutionCostWithinTick**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**currentExecutionCostInCurrentTick**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**scheduler**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**task**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Get Accessor(s)

## isActive

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## length

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## activate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITaskQueueOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/task-queue/itaskqueueoptions) | ✘  | ✘ | ✘ | - |

## deactivate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## enqueue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt; &#124; QueueTask&lt;T&gt;[] |

**&#128966; Parameter(s)**

_**itemOrItems**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IQueueableItem](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/task-queue/iqueueableitem)&lt;T&gt; &#124; QueueableFunction &#124; [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt; &#124; QueueTask&lt;T&gt;[] &#124; (IQueueableItem&lt;T&gt; &#124; QueueableFunction)[] | ✘  | ✘ | ✘ | - |

_**costOrCosts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number &#124; number[] &#124; undefined | ✔  | ✘ | ✘ | - |

## createQueueTask

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt; |

**&#128966; Parameter(s)**

_**item**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IQueueableItem](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/task-queue/iqueueableitem)&lt;T&gt; &#124; QueueableFunction | ✘  | ✘ | ✘ | - |

_**cost**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128966; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bound | ✘  |

## dequeue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**delta**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number &#124; undefined | ✔  | ✘ | ✘ | - |

## clear

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## resolve

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**task**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**resolve**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | (value: void &#124; PromiseLike&lt;void&gt;) =&gt; void | ✘  | ✘ | ✘ | - |

## reject

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**task**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [QueueTask](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/task-queue/queuetask)&lt;T&gt; | ✘  | ✘ | ✘ | - |

_**reject**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | (value: unknown) =&gt; void | ✘  | ✘ | ✘ | - |

_**reason**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown | ✘  | ✘ | ✘ | - |