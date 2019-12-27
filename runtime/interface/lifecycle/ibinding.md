# IBinding

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## interceptor

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | this |

## locator

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IServiceLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iservicelocator) |

## $scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/iscope) &#124; undefined |

### &#128366; Summary

The name of the `replace-part` template that this binding was declared inside of (if any, otherwise this property is `undefined`).
This property is passed through the AST during evaluation, which allows the scope traversal to go up to the scope of the `replace-part` if a property does not exist inside the `replaceable`.

## part

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## $state

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [State](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/state) |

# &#128712; Method(s)

## $bind

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**part**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## $unbind

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |