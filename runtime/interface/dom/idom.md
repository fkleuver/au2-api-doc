# IDOM

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                           |
| ---- | ------------------------------------------------------------------------------------ |
| T    | [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) |

# &#128712; Method(s)

## addEventListener

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**eventName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**publisher**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## appendChild

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**parent**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**child**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type   | Constraint |
| ------ | ---------- |
| TClone | T          |

## cloneNode

| Return Type                       |
|-----------------------------------|
| TClone |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**deep**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## convertToRenderLocation

| Return Type                       |
|-----------------------------------|
| [IRenderLocation](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/irenderlocation)&lt;T&gt; |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createDocumentFragment

| Return Type                       |
|-----------------------------------|
| T |

**&#128966; Parameter(s)**

_**markupOrNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## createNodeSequence

| Return Type                       |
|-----------------------------------|
| [INodeSequence](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inodesequence)&lt;T&gt; |

**&#128966; Parameter(s)**

_**fragment**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createElement

| Return Type                       |
|-----------------------------------|
| T |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createCustomEvent

| Return Type                       |
|-----------------------------------|
| unknown |

**&#128966; Parameter(s)**

_**eventType**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## dispatchEvent

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**evt**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createNodeObserver

| Return Type                       |
|-----------------------------------|
| unknown |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**cb**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**init**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createTemplate

| Return Type                       |
|-----------------------------------|
| T |

**&#128966; Parameter(s)**

_**markup**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## createTextNode

| Return Type                       |
|-----------------------------------|
| T |

**&#128966; Parameter(s)**

_**text**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Returns the effective parentNode according to Aurelia's component hierarchy.
Used by Aurelia to find the closest parent controller relative to a node.
This method supports 3 additional scenarios that `node.parentNode` does not support:
- Containerless elements. The parentNode in this case is a comment precending the element under specific conditions, rather than a node wrapping the element.
- ShadowDOM. If a `ShadowRoot` is encountered, this method retrieves the associated controller via the metadata api to locate the original host.
- Portals. If the provided node was moved to a different location in the DOM by a `portal` attribute, then the original parent of the node will be returned.

**Parameter(s)**

| Name | Description                      |
| ---- | -------------------------------- |
| node |  The node to get the parent for. |

**Returns**

Either the closest parent node, the closest `IRenderLocation` (comment node that is the containerless host), original portal host, or `null` if this is either the absolute document root or a disconnected node.

## getEffectiveParentNode

| Return Type                       |
|-----------------------------------|
| T &#124; null |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Set the effective parentNode, overriding the DOM-based structure that `getEffectiveParentNode` otherwise defaults to.
Used by Aurelia's `portal` template controller to retain the linkage between the portaled nodes (after they are moved to the portal target) and the original `portal` host.

**Parameter(s)**

| Name         | Description                                                                                                           |
| ------------ | --------------------------------------------------------------------------------------------------------------------- |
| nodeSequence |  The node sequence whose children that, when `getEffectiveParentNode` is called on, return the supplied `parentNode`. |
| parentNode   |  The node to return when `getEffectiveParentNode` is called on any child of the supplied `nodeSequence`.              |

## setEffectiveParentNode

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**nodeSequence**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**parentNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Set the effective parentNode, overriding the DOM-based structure that `getEffectiveParentNode` otherwise defaults to.
Used by Aurelia's `portal` template controller to retain the linkage between the portaled nodes (after they are moved to the portal target) and the original `portal` host.

**Parameter(s)**

| Name       | Description                                                                                    |
| ---------- | ---------------------------------------------------------------------------------------------- |
| childNode  |  The node that, when `getEffectiveParentNode` is called on, returns the supplied `parentNode`. |
| parentNode |  The node to return when `getEffectiveParentNode` is called on the supplied `childNode`.       |

## setEffectiveParentNode

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**childNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**parentNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## insertBefore

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**nodeToInsert**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**referenceNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## isMarker

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## isNodeInstance

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**potentialNode**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## isRenderLocation

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## makeTarget

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## registerElementResolver

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**resolver**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## remove

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## removeEventListener

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**eventName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**subscriber**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**publisher**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## setAttribute

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |