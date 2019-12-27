# ICustomAttributeController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IComponentController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icomponentcontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                                                  |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| C    | [ICustomAttributeViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributeviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

## vmKind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.customAttribute |

### &#128366; Summary

**Inheritdoc**

## viewModel

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C |

### &#128366; Summary

**Inheritdoc**

## bindingContext

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | C & { [x: string]: unknown; [x: number]: unknown; } |

### &#128366; Summary

The scope that belongs to this custom attribute. This property will always be defined when the `state` property of this view indicates that the view is currently bound.
The `scope` will be set during `bind()` and unset during `unbind()`.
The scope's `bindingContext` will be the same instance as this controller's `bindingContext` property.

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/class/binding-context/scope) &#124; undefined |

## controllers

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

## bindings

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |