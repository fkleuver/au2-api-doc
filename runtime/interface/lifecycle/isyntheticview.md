# &#128366; Summary

The controller for a synthetic view, that is, a controller created by an `IViewFactory`.
A synthetic view, typically created when rendering a template controller (`if`, `repeat`, etc), is a renderable component with mountable DOM nodes that has no user view model.
It has either its own synthetic binding context or is locked to some externally sourced scope (in the case of `au-compose`)

# ISyntheticView

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IRenderableController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/irenderablecontroller)&lt;T, IViewModel&lt;T&gt;&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Property(ies)

## vmKind

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ViewModelKind.synthetic |

## viewModel

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

## bindingContext

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | undefined |

### &#128366; Summary

The scope that belongs to this view. This property will always be defined when the `state` property of this view indicates that the view is currently bound.
The `scope` may be set during `bind()` and unset during `unbind()`, or it may be statically set during rendering with `lockScope()`.

## scope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/class/binding-context/scope) &#124; undefined |

### &#128366; Summary

The compiled render context used for rendering this view. Compilation was done by the `IViewFactory` prior to creating this view.

## context

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ICompiledRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/icompiledrendercontext)&lt;T&gt; |

### &#128366; Summary

The names of the `replace` parts that were declared in the same scope as this view's template.
The `replaceable` template controllers with those names will use this view's scope as the outer scope for properties that don't exist on the inner scope.

## scopeParts

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] |

## isStrictBinding

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

### &#128366; Summary

The physical DOM nodes that will be appended during the `mount()` operation.

## nodes

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;T&gt; |

### &#128366; Summary

The DOM node that this view will be mounted to.

## location

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderLocation](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/irenderlocation)&lt;T&gt; &#124; undefined |

# &#128712; Method(s)

### &#128366; Summary

Lock this view's scope to the provided `IScope`. The scope, which is normally set during `bind()`, will then not change anymore.
This is used by `au-compose` to set the binding context of a view to a particular component instance.

**Parameter(s)**

| Name  | Description                      |
| ----- | -------------------------------- |
| scope |  The scope to lock this view to. |

## lockScope

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Set the DOM node that this view will be mounted to, as well as the mounting mechanism that will be used.

**Parameter(s)**

| Name          | Description                                               |
| ------------- | --------------------------------------------------------- |
| location      |  The `IRenderLocation` that this view will be mounted to. |
| mountStrategy |  The method that will be used during mounting.            |

## hold

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**location**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**mountStrategy**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Mark this view as not-in-use, so that it can either be dereferenced and garbage-collected, or returned to cache if caching was enabled for this view.
If this view is not attached when this method is called, it will immediately be unmounted (if it was still mounted) and returned to cache (if it could be cached).

**Parameter(s)**

| Name  | Description                                              |
| ----- | -------------------------------------------------------- |
| flags |  The flags to pass to the synchronous unmount operation. |

## release

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |