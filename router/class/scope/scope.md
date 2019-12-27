| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**router**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRouter](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouter) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**hasScope**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**owningScope**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) &#124; null | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**viewport**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) &#124; null | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**viewportScope**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) &#124; null | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**rootComponentType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| ResourceType&lt;Constructable&lt;{}&gt;, ICustomElementViewModel&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;, {}&gt; &#124; null | ✔  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**id**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**scope**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**parent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**children**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**replacedChildren**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**path**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**enabled**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Support collection feature in viewport scopes

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**childCollections**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Get Accessor(s)

## isViewport

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## isViewportScope

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## passThroughScope

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## owner

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## enabledChildren

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## hoistedChildren

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## enabledViewports

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## viewportInstruction

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## getEnabledViewports

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Record&lt;string, [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport)&gt; |

**&#128966; Parameter(s)**

_**viewportScopes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope)[] | ✘  | ✘ | ✘ | - |

## getOwnedViewports

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport)[] |

**&#128966; Parameter(s)**

_**includeDisabled**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

## getOwnedScopes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope)[] |

**&#128966; Parameter(s)**

_**includeDisabled**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

### &#128366; Summary

Note: This can't change state other than the instructions!

## findViewports

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [IFindViewportsResult](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/scope/ifindviewportsresult) |

**&#128966; Parameter(s)**

_**instructions**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] | ✘  | ✘ | ✘ | - |

_**alreadyFound**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] | ✘  | ✘ | ✘ | - |

_**disregardViewports**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

## foundViewportScope

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] |

**&#128966; Parameter(s)**

_**instruction**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction) | ✘  | ✘ | ✘ | - |

_**viewportScope**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) | ✘  | ✘ | ✘ | - |

## foundViewport

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] |

**&#128966; Parameter(s)**

_**instruction**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction) | ✘  | ✘ | ✘ | - |

_**viewport**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) | ✘  | ✘ | ✘ | - |

_**withoutViewports**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |

_**doesntNeedViewportDescribed**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

## addViewport

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Element &#124; null | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) &#124; null | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IViewportOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/viewport/iviewportoptions) | ✔  | ✘ | ✘ | {} |

## removeViewport

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**viewport**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Element &#124; null | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) &#124; null | ✘  | ✘ | ✘ | - |

## addViewportScope

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Element &#124; null | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IViewportScopeOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/viewport-scope/iviewportscopeoptions) | ✔  | ✘ | ✘ | {} |

## removeViewportScope

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**viewportScope**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) | ✘  | ✘ | ✘ | - |

## addChild

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**scope**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) | ✘  | ✘ | ✘ | - |

## removeChild

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**scope**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) | ✘  | ✘ | ✘ | - |

## clearReplacedChildren

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## disableReplacedChildren

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## reenableReplacedChildren

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## allViewports

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport)[] |

**&#128966; Parameter(s)**

_**includeDisabled**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

_**includeReplaced**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

## allScopes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope)[] |

**&#128966; Parameter(s)**

_**includeDisabled**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

_**includeReplaced**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | false |

## reparentViewportInstructions

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] &#124; null |

## findMatchingRoute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [FoundRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/found-route/foundroute) &#124; null |

**&#128966; Parameter(s)**

_**path**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## canLeave

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, async | ✘ | Promise&lt;boolean&gt; |

## findMatchingRouteInRoutes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [FoundRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/found-route/foundroute) &#124; null |

**&#128966; Parameter(s)**

_**path**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**routes**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute)[] &#124; null | ✘  | ✘ | ✘ | - |

## ensureProperRoute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute) |

**&#128966; Parameter(s)**

_**route**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute) | ✘  | ✘ | ✘ | - |