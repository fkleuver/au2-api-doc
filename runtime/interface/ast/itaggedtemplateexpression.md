# ITaggedTemplateExpression

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IExpression](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/ast/iexpression) |

# &#128712; Property(ies)

## $kind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ExpressionKind.TaggedTemplate |

## cooked

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] & { raw?: readonly string[] &#124; undefined; } |

## func

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | IsLeftHandSide |

## expressions

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly IsAssign[] |