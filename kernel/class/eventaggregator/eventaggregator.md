## &#128366; Summary

Enables loosely coupled publish/subscribe messaging.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IEventAggregator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/variable/eventaggregator/ieventaggregator) |

## &#128712; Property(ies)

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## publish

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**channelOrInstance**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T extends Constructable&lt;{}&gt; ? InstanceType&lt;T&gt; : T | ✘  | ✘ | ✘ | - |

_**data**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown | ✔  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## subscribe

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

**&#128966; Parameter(s)**

_**channelOrType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | EventAggregatorCallback&lt;T extends Constructable&lt;{}&gt; ? InstanceType&lt;T&gt; : T&gt; | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint                            |
| ---- | ------------------------------------- |
| T    | string &#124; Constructable&lt;{}&gt; |

## subscribeOnce

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

**&#128966; Parameter(s)**

_**channelOrType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T | ✘  | ✘ | ✘ | - |

_**callback**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | EventAggregatorCallback&lt;T&gt; | ✘  | ✘ | ✘ | - |