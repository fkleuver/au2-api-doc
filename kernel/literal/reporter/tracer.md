# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Tracer

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { enabled: boolean; liveLoggingEnabled: boolean; liveWriter: [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter); enter(objName: string, methodName: string, args: unknown[] &#124; null): void; leave(): void; writeStack(writer: ITraceWriter): void; flushAll(writer: ITraceWriter &#124; null): void; enableLiveLogging: typeof enableLiveLogging; disableLiveLogging(): void; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### enabled

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { enabled: boolean; liveLoggingEnabled: boolean; liveWriter: [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter); enter(objName: string, methodName: string, args: unknown[] &#124; null): void; leave(): void; writeStack(writer: ITraceWriter): void; flushAll(writer: ITraceWriter &#124; null): void; enableLiveLogging: typeof enableLiveLogging; disableLiveLogging(): void; } | ✘  | ✘ |

### Value

false

### liveLoggingEnabled

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { enabled: boolean; liveLoggingEnabled: boolean; liveWriter: [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter); enter(objName: string, methodName: string, args: unknown[] &#124; null): void; leave(): void; writeStack(writer: ITraceWriter): void; flushAll(writer: ITraceWriter &#124; null): void; enableLiveLogging: typeof enableLiveLogging; disableLiveLogging(): void; } | ✘  | ✘ |

### Value

false

### liveWriter

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { enabled: boolean; liveLoggingEnabled: boolean; liveWriter: [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter); enter(objName: string, methodName: string, args: unknown[] &#124; null): void; leave(): void; writeStack(writer: ITraceWriter): void; flushAll(writer: ITraceWriter &#124; null): void; enableLiveLogging: typeof enableLiveLogging; disableLiveLogging(): void; } | ✘  | ✘ |

### Value

null! as ITraceWriter

### enableLiveLogging

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { enabled: boolean; liveLoggingEnabled: boolean; liveWriter: [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter); enter(objName: string, methodName: string, args: unknown[] &#124; null): void; leave(): void; writeStack(writer: ITraceWriter): void; flushAll(writer: ITraceWriter &#124; null): void; enableLiveLogging: typeof enableLiveLogging; disableLiveLogging(): void; } | ✔  | ✘ |

### Value

-

### &#128712; Method(s)

### &#128366; Summary

Call this at the start of a method/function.
Each call to `enter` **must** have an accompanying call to `leave` for the tracer to work properly.

**Parameter(s)**

| Name       | Description                                                                                                                         |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| objName    |  Any human-friendly name to identify the traced object with.                                                                        |
| methodName |  Any human-friendly name to identify the traced method with.                                                                        |
| args       |  Pass in `Array.prototype.slice.call(arguments)` to also trace the parameters, or `null` if this is not needed (to save memory/cpu) |

## enter

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**objName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**methodName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**args**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown[] &#124; null | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Call this at the end of a method/function. Pops one trace item off the stack.

## leave

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

### &#128366; Summary

Writes only the trace info leading up to the current method call.

**Parameter(s)**

| Name   | Description                        |
| ------ | ---------------------------------- |
| writer |  An object to write the output to. |

## writeStack

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**writer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Writes all trace info captured since the previous flushAll operation.

**Parameter(s)**

| Name   | Description                                                                      |
| ------ | -------------------------------------------------------------------------------- |
| writer |  An object to write the output to. Can be null to simply reset the tracer state. |

## flushAll

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**writer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITraceWriter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/reporter/itracewriter) &#124; null | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Stops writing out each trace info item as they are traced.

## disableLiveLogging

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |