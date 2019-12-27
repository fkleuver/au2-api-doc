# &#128366; Summary

A representation of `IController` specific to a custom element whose `beforeCompile` hook is about to be invoked (if present).
It has the same properties as `IDryCustomElementController`, as well as a render context (hence 'contextual').

# IContextualCustomElementController

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IDryCustomElementController](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/idrycustomelementcontroller)&lt;T, C&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

| Type | Constraint                                                                                                    |
| ---- | ------------------------------------------------------------------------------------------------------------- |
| C    | [IViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewmodel)&lt;T&gt; |

# &#128712; Property(ies)

### &#128366; Summary

The non-compiled render context used for compiling this component's `CustomElementDefinition`.

## context

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/irendercontext)&lt;T&gt; |