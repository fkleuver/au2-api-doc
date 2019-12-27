## &#128366; Summary

An attribute, with either a binding command or an interpolation, whose target is the html
attribute of the element.
This will never target a bindable property of a custom attribute or element;

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✘ | ✔ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**syntax**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**command**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } &#124; null | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**expression**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;StrictPrimitive&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression &#124; IInterpolationExpression &#124; IForOfStatement &#124; null | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**syntax**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**command**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**expression**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flags**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |