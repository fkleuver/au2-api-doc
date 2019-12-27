# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Literal(s)

## DOM

| Type                        | Array                           |
|-----------------------------|---------------------------------|
| [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt; & { readonly isInitialized: boolean; readonly scheduler: [IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler); initialize(dom: IDOM&lt;INode&gt;): void; destroy(): void; } | ✘ |

## 🟆 Member(s)

### &#128712; Attribute(s)

| Object                        |
|-------------------------------|
| ✔ |

### &#128712; Assignment(s)

### niDOM

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { scheduler: never; isInitialized: boolean; initialize(dom: [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt;): void; destroy(): void; IDOM.addEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.appendChild(parent: INode, child: INode): void; IDOM.cloneNode&lt;TClone&gt;(node: TClone, deep?: boolean &#124; undefined): TClone; IDOM.convertToRenderLocation(node: INode): IRenderLocation&lt;INode&gt;; IDOM.createDocumentFragment(markupOrNode?: string &#124; INode &#124; undefined): INode; IDOM.createNodeSequence(fragment: INode &#124; null): INodeSequence&lt;INode&gt;; IDOM.createElement(name: string): INode; IDOM.createCustomEvent(eventType: string, options?: unknown): unknown; IDOM.dispatchEvent(evt: unknown): void; IDOM.createNodeObserver?(node: INode, cb: (...args: unknown[]) =&gt; void, init: unknown): unknown; IDOM.createTemplate(markup?: string &#124; undefined): INode; IDOM.createTextNode(text: string): INode; IDOM.getEffectiveParentNode(node: INode): INode &#124; null; IDOM.setEffectiveParentNode(nodeSequence: INodeSequence&lt;INode&gt;, parentNode: INode): void; IDOM.setEffectiveParentNode(childNode: INode, parentNode: INode): void; IDOM.insertBefore(nodeToInsert: INode, referenceNode: INode): void; IDOM.isMarker(node: unknown): node is INode; IDOM.isNodeInstance(potentialNode: unknown): potentialNode is INode; IDOM.isRenderLocation(node: unknown): node is IRenderLocation&lt;INode&gt;; IDOM.makeTarget(node: INode): void; IDOM.registerElementResolver(container: IContainer, resolver: IResolver&lt;any&gt;): void; IDOM.remove(node: INode): void; IDOM.removeEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.setAttribute(node: INode, name: string, value: unknown): void; } | ✘  | ✔ |

### Value

-

### scheduler

| Type                      | Shorthand                         | Spread                        |
|---------------------------|:---------------------------------:|:-----------------------------:|
| { scheduler: never; isInitialized: boolean; initialize(dom: [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt;): void; destroy(): void; IDOM.addEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.appendChild(parent: INode, child: INode): void; IDOM.cloneNode&lt;TClone&gt;(node: TClone, deep?: boolean &#124; undefined): TClone; IDOM.convertToRenderLocation(node: INode): IRenderLocation&lt;INode&gt;; IDOM.createDocumentFragment(markupOrNode?: string &#124; INode &#124; undefined): INode; IDOM.createNodeSequence(fragment: INode &#124; null): INodeSequence&lt;INode&gt;; IDOM.createElement(name: string): INode; IDOM.createCustomEvent(eventType: string, options?: unknown): unknown; IDOM.dispatchEvent(evt: unknown): void; IDOM.createNodeObserver?(node: INode, cb: (...args: unknown[]) =&gt; void, init: unknown): unknown; IDOM.createTemplate(markup?: string &#124; undefined): INode; IDOM.createTextNode(text: string): INode; IDOM.getEffectiveParentNode(node: INode): INode &#124; null; IDOM.setEffectiveParentNode(nodeSequence: INodeSequence&lt;INode&gt;, parentNode: INode): void; IDOM.setEffectiveParentNode(childNode: INode, parentNode: INode): void; IDOM.insertBefore(nodeToInsert: INode, referenceNode: INode): void; IDOM.isMarker(node: unknown): node is INode; IDOM.isNodeInstance(potentialNode: unknown): potentialNode is INode; IDOM.isRenderLocation(node: unknown): node is IRenderLocation&lt;INode&gt;; IDOM.makeTarget(node: INode): void; IDOM.registerElementResolver(container: IContainer, resolver: IResolver&lt;any&gt;): void; IDOM.remove(node: INode): void; IDOM.removeEventListener(eventName: string, subscriber: unknown, publisher?: unknown, options?: unknown): void; IDOM.setAttribute(node: INode, name: string, value: unknown): void; } | ✘  | ✘ |

### Value

(void 0)!

### &#128712; Get Accessor(s)

### isInitialized

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| - | - |

### &#128712; Method(s)

## initialize

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |

**&#128966; Parameter(s)**

_**dom**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt; | ✘  | ✘ | ✘ | - |

## destroy

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| - | ✘ | void |