# &#128366; Summary

A render context that wraps an `IContainer` and must be compiled before it can be used for rendering.

# IRenderContext

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Property(ies)

## dom

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;T&gt; |

## parts

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; &#124; undefined |

### &#128366; Summary

The `CustomElementDefinition` that this `IRenderContext` was created with.
If a `PartialCustomElementDefinition` was used to create this context, then this property will be the return value of `CustomElementDefinition.getOrCreate`.

## definition

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt; |

### &#128366; Summary

The `IContainer` (which may be, but is not guaranteed to be, an `IRenderContext`) that this `IRenderContext` was created with.

## parentContainer

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

# &#128712; Method(s)

### &#128366; Summary

Prepare this factory for creating child controllers. Only applicable for custom elements.

**Parameter(s)**

| Name     | Description                                                                                                                |
| -------- | -------------------------------------------------------------------------------------------------------------------------- |
| instance |  The component instance to make available to child components if this context's definition has `injectable` set to `true`. |

## beginChildComponentOperation

| Return Type                       |
|-----------------------------------|
| [IRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/irendercontext)&lt;T&gt; |

**&#128966; Parameter(s)**

_**instance**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Compiles the backing `CustomElementDefinition` (if needed) and returns the compiled `IRenderContext` that exposes the compiled `CustomElementDefinition` as well as rendering operations.
This operation is idempotent.

**Returns**

The compiled `IRenderContext`.

## compile

| Return Type                       |
|-----------------------------------|
| [ICompiledRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/icompiledrendercontext)&lt;T&gt; |

### &#128366; Summary

Creates an (or returns the cached) `IViewFactory` that can be used to create synthetic view controllers.

**Parameter(s)**

| Name | Description                                                                                                                                                                        |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| name |  Optional. The `name` that will be used by `replaceable` part lookups or the `| view` value converter. Defaults to the `name` property of the passed-in `CustomElementDefinition`. |

**Returns**

Either a new `IViewFactory` (if this is the first call), or a cached one.

## getViewFactory

| Return Type                       |
|-----------------------------------|
| [IViewFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/iviewfactory)&lt;T&gt; |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |