# &#128366; Summary

A compiled `IRenderContext` that is ready to be used for creating component instances, and rendering them.

# IComponentFactory

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICompiledRenderContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/interface/render-context/icompiledrendercontext)&lt;T&gt;, [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Method(s)

### &#128366; Summary

Creates a new component instance based on the provided `resourceKey`.
It is only safe to override the generic type argument if you know / own the component type associated with the name.

**Parameter(s)**

| Name        | Description                                                     |
| ----------- | --------------------------------------------------------------- |
| resourceKey |  The (full) resource key as returned from the `keyFrom` helper. |

**Returns**

A new instance of the requested component. Will throw an error if the registration does not exist.

**Example**

```ts
// Create a new instance of the 'au-compose' custom element
const elementInstance = factory.createComponent<Compose>(CustomElement.keyFrom('au-compose'));
  // Create a new instance of the 'if' template controller
  const attributeInstance = factory.createComponent<If>(CustomAttribute.keyFrom('if'));
    // Dynamically create a new instance of a custom element
    const attributeInstance = factory.createComponent(CustomElement.keyFrom(name));
    ```

### &#128966; Type Parameter(s)

| Type       | Constraint |
| ---------- | ---------- |
| TViewModel | -          |

## createComponent

| Return Type                       |
|-----------------------------------|
| TViewModel |

**&#128966; Parameter(s)**

_**resourceKey**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Release any resources that were stored by `getComponentFactory()`.

## dispose

| Return Type                       |
|-----------------------------------|
| void |