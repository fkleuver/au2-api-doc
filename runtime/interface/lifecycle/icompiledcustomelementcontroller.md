# &#128366; Summary

A representation of `IController` specific to a custom element whose `afterCompile` hook is about to be invoked (if present).
It has the same properties as `IContextualCustomElementController`, except the context is now compiled (hence 'compiled'), as well as the nodes, and projector.

# ICompiledCustomElementController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IContextualCustomElementController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icontextualcustomelementcontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                    |
| ---- | ------------------------------------------------------------------------------------------------------------- |
| C    | [IViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

### &#128366; Summary

The compiled render context used for hydrating this controller.

## context

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ICompiledRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/icompiledrendercontext)&lt;T&gt; |

### &#128366; Summary

The names of the `replace` parts that were declared in the same scope as this component's template.
The `replaceable` template controllers with those names will use this components's scope as the outer scope for properties that don't exist on the inner scope.

## scopeParts

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | readonly string[] |

## isStrictBinding

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

### &#128366; Summary

The projector used for mounting the `nodes` of this controller. Typically this will be one of:
- `HostProjector` (the host is a normal DOM node)
- `ShadowDOMProjector` (the host is a shadow root)
- `ContainerlessProjector` (the host is a comment node)

## projector

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IElementProjector](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/interface/custom-element/ielementprojector)&lt;T&gt; |

### &#128366; Summary

The physical DOM nodes that will be appended during the `mount()` operation.

## nodes

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;T&gt; |