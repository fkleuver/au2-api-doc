# &#128366; Summary

The main interface to the logging API.
Inject this as a dependency in your components to add centralized, configurable logging capabilities to your application.

# ILogger

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

### &#128366; Summary

The root `ILogger` instance. On the root logger itself, this property circularly references the root. It is never null.
When using `.scopeTo`, a new `ILogger` is created. That new logger will have the `root` property set to the global (non-scoped) logger.

## root

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) |

### &#128366; Summary

The parent `ILogger` instance. On the root logger itself, this property circularly references the root. It is never null.
When using `.scopeTo`, a new `ILogger` is created. That new logger will have the `parent` property set to the logger that it was created from.

## parent

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) |

### &#128366; Summary

The scopes that this logger was created for, if any.

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] |

### &#128366; Summary

The global logger configuration.

## config

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILogConfig](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogconfig) |

# &#128712; Method(s)

### &#128366; Summary

Write to TRC output, if the configured `LogLevel` is set to `trace`.
Intended for the most detailed information about internal app state.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## trace

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to TRC output, if the configured `LogLevel` is set to `trace`.
Intended for the most detailed information about internal app state.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## trace

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to DBG output, if the configured `LogLevel` is set to `debug` or lower.
Intended for information that is useful for debugging during development and has no long-term value.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## debug

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to DBG output, if the configured `LogLevel` is set to `debug` or lower.
Intended for information that is useful for debugging during development and has no long-term value.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## debug

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to trace UBF, if the configured `LogLevel` is set to `info` or lower.
Intended for information about the general flow of the application that has long-term value.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## info

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to trace UBF, if the configured `LogLevel` is set to `info` or lower.
Intended for information about the general flow of the application that has long-term value.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## info

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to WRN output, if the configured `LogLevel` is set to `warn` or lower.
Intended for unexpected circumstances that require attention but do not otherwise cause the current flow of execution to stop.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## warn

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to WRN output, if the configured `LogLevel` is set to `warn` or lower.
Intended for unexpected circumstances that require attention but do not otherwise cause the current flow of execution to stop.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## warn

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to ERR output, if the configured `LogLevel` is set to `error` or lower.
Intended for unexpected circumstances that cause the flow of execution in the current activity to stop but do not cause an app-wide failure.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## error

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to ERR output, if the configured `LogLevel` is set to `error` or lower.
Intended for unexpected circumstances that cause the flow of execution in the current activity to stop but do not cause an app-wide failure.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## error

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to FTL output, if the configured `LogLevel` is set to `fatal` or lower.
Intended for unexpected circumstances that cause an app-wide failure or otherwise require immediate attention.

**Parameter(s)**

| Name           | Description                                                                                                                                                                                                                                                                   |
| -------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| getMessage     |  A function to build the message to pass to the `ILogEventFactory`. Only called if the configured `LogLevel` dictates that these messages be emitted. Use this when creating the log message is potentially expensive and should only be done if the log is actually emitted. |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory`                                                                                                                                                                                              |

## fatal

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**getMessage**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Write to FTL output, if the configured `LogLevel` is set to `fatal` or lower.
Intended for unexpected circumstances that cause an app-wide failure or otherwise require immediate attention.

**Parameter(s)**

| Name           | Description                                                                      |
| -------------- | -------------------------------------------------------------------------------- |
| message        |  The message to pass to the `ILogEventFactory`.                                  |
| optionalParams |  Any additional, optional params that should be passed to the `ILogEventFactory` |

## fatal

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**message**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**optionalParams**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Create a new logger with an additional permanent prefix added to the logging outputs.
When chained, multiple scopes are separated by a dot.
This is preliminary API and subject to change before alpha release.

**Example**

```ts
export class MyComponent {
  constructor(@ILogger private logger: ILogger) {
    this.logger.debug('before scoping');
    // console output: '[DBG] before scoping'
    this.logger = logger.scopeTo('MyComponent');
    this.logger.debug('after scoping');
    // console output: '[DBG MyComponent] after scoping'
  }
  public doStuff(): void {
    const logger = this.logger.scopeTo('doStuff()');
    logger.debug('doing stuff');
    // console output: '[DBG MyComponent.doStuff()] doing stuff'
  }
}
```

## scopeTo

| Return Type                       |
|-----------------------------------|
| [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |