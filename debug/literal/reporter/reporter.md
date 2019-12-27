# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## Reporter

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { level: [LogLevel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/enum/reporter/loglevel); write(code: number, ...params: unknown[]): void; error(code: number, ...params: unknown[]): Error; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### RuntimeReporter

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { level: [LogLevel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/enum/reporter/loglevel); write(code: number, ...params: unknown[]): void; error(code: number, ...params: unknown[]): Error; } | ✘  | ✔ |

### Value

-

### &#128712; Get Accessor(s)

### level

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| - | - |

### &#128712; Method(s)

## write

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**code**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number | ✘  | ✘ | ✘ | - |

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown[] | ✔  | ✔ | ✘ | - |

## error

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | Error |

**&#128966; Parameter(s)**

_**code**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number | ✘  | ✘ | ✘ | - |

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown[] | ✔  | ✔ | ✘ | - |