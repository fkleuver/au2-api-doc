# &#128366; Summary

A compiled `IRenderContext` that can create instances of `INodeSequence` (based on the template of the compiled definition)
and begin a component operation to create new component instances.

# ICompiledRenderContext

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/irendercontext)&lt;T&gt; |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Property(ies)

### &#128366; Summary

The compiled `CustomElementDefinition`.
If the passed-in `PartialCustomElementDefinition` had a non-null `template` and `needsCompile` set to `true`, this will be a new definition created by the `ITemplateCompiler`.

## compiledDefinition

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt; |

# &#128712; Method(s)

### &#128366; Summary

Returns a new `INodeSequence` based on the document fragment from the compiled `CustomElementDefinition`.
A new instance will be created from a clone of the fragment on each call.

**Returns**

An new instance of `INodeSequence` if there is a template, otherwise a shared empty instance.

## createNodes

| Return Type                       |
|-----------------------------------|
| [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;T&gt; |

### &#128366; Summary

Prepare this render context for creating a new component instance.
All parameters are optional injectable dependencies, that is: only those that are actually needed by the to-be-created component, need to be provided in order for that component to work.
To avoid possible memory leaks, don't forget to call `dispose()` on the returned `IComponentFactory` after creating a component.

**Parameter(s)**

| Name             | Description                                                                                                                                                                             |
| ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| parentController |  The `IController` of the immediate parent of the to-be-created component. Not used by any built-in components.                                                                         |
| host             |  The DOM node that declared the component, or the node that the component will be mounted to (in case of containerless). Used by some built-in custom attributes.                       |
| instruction      |  The hydrate instruction that resulted in the creation of this render context. Only used by `au-compose`.                                                                               |
| viewFactory      |  The `IViewFactory` that was created from the template that the template controller was placed on. Only applicable for template controllers. Used by all built-in template controllers. |
| location         |  The DOM node that the nodes created by the `IViewFactory` should be mounted to. Only applicable for template controllers. Used by all built-in template controllers.                   |

## getComponentFactory

| Return Type                       |
|-----------------------------------|
| [IComponentFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/icomponentfactory)&lt;T&gt; |

**&#128966; Parameter(s)**

_**parentController**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**host**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**instruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**viewFactory**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**location**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## render

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**controller**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**targets**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**templateDefinition**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**host**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**parts**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## renderInstructions

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**instructions**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**controller**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**target**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**parts**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |