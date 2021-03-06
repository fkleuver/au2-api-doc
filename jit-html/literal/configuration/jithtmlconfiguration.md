# &#128366; Summary

A DI configuration object containing html-specific (but environment-agnostic) registrations:
- `RuntimeHtmlConfiguration` from `@aurelia/runtime-html`
- `DefaultComponents` from `@aurelia/jit`
- `DefaultBindingSyntax` from `@aurelia/jit`
- `DefaultBindingLanguage` from `@aurelia/jit`
- `DefaultComponents`
- `DefaultBindingLanguage`

# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## JitHtmlConfiguration

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| { register(container: [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer)): IContainer; createContainer(): IContainer; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Method(s)

### &#128366; Summary

Apply this configuration to the provided container.

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Create a new container with this configuration applied to it.

## createContainer

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |