# IAttributeBindingInstruction

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction) |

# &#128712; Property(ies)

## type

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | HTMLTargetedInstructionType.attributeBinding |

## from

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string &#124; IAccessThisExpression &#124; IAccessScopeExpression &#124; IArrayLiteralExpression &#124; IObjectLiteralExpression &#124; IPrimitiveLiteralExpression&lt;StrictPrimitive&gt; &#124; ITemplateExpression &#124; ICallFunctionExpression &#124; ICallMemberExpression &#124; ICallScopeExpression &#124; IAccessMemberExpression &#124; IAccessKeyedExpression &#124; ITaggedTemplateExpression &#124; IUnaryExpression &#124; IBinaryExpression &#124; IConditionalExpression &#124; IAssignExpression &#124; IValueConverterExpression &#124; IBindingBehaviorExpression |

### &#128366; Summary

`attr` and `to` have the same value on a normal attribute
Will be different on `class` and `style`
on `class`: attr = `class` (from binding command), to = attribute name
on `style`: attr = `style` (from binding command), to = attribute name

## attr

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

## to

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |