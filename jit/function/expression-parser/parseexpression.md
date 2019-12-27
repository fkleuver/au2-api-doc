# parseExpression

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | TType extends BindingType.Interpolation ? [IInterpolationExpression](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/ast/iinterpolationexpression) : TType extends BindingType.ForCommand ? [IForOfStatement](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/ast/iforofstatement) : IsBindingBehavior | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type  | Constraint                                                                                                        |
| ----- | ----------------------------------------------------------------------------------------------------------------- |
| TType | [BindingType](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/binding/enum/expression-parser/bindingtype) |

## &#128966; Parameter(s)

_**input**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**bindingType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | TType &#124; undefined | ✔  | ✘ | ✘ | - |