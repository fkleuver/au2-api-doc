## &#128366; Summary

Either an attribute on an custom element that maps to a declared bindable property of that element,
a single-value bound custom attribute, or one of several bindables that were extracted from the attribute
value of a custom attribute with multiple bindings usage.
This will always target a bindable property of a custom attribute or element;

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✘ | ✔ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**command**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } &#124; null | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindable**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [BindableInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/bindableinfo) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**expression**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;StrictPrimitive&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression &#124; IInterpolationExpression &#124; IForOfStatement &#124; null | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**rawValue**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**target**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**command**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindable**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**expression**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**rawValue**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**target**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flags**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| - | ✘ | - | - |