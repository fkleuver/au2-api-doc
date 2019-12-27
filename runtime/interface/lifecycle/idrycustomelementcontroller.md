# &#128366; Summary

A representation of `IController` specific to a custom element whose `create` hook is about to be invoked (if present).
It is not yet hydrated (hence 'dry') with any rendering-specific information.

# IDryCustomElementController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IComponentController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icomponentcontroller)&lt;T, C&gt;, [IRenderableController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/irenderablecontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                    |
| ---- | ------------------------------------------------------------------------------------------------------------- |
| C    | [IViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

## vmKind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.customElement |

### &#128366; Summary

The scope that belongs to this custom element. This property is set immediately after the controller is created and is always guaranteed to be available.
It may be overwritten by end user during the `create()` hook.
By default, the scope's `bindingContext` will be the same instance as this controller's `bindingContext` property.

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/class/binding-context/scope) |

### &#128366; Summary

The physical DOM node that this controller's `nodes` will be mounted to.

## host

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T |