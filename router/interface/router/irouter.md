# IRouter

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## isNavigating

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## activeComponents

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction)[] |

## rootScope

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) &#124; null |

## activeRoute

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute) &#124; undefined |

## container

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

## instructionResolver

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [InstructionResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/instruction-resolver/instructionresolver) |

## navigator

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Navigator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/navigator/navigator) |

## navigation

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [BrowserViewerStore](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/browser-viewer-store/browserviewerstore) |

## hookManager

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [HookManager](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/hook-manager/hookmanager) |

## linkHandler

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LinkHandler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/link-handler/linkhandler) |

## navs

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | Readonly&lt;Record&lt;string, [Nav](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav/nav)&gt;&gt; |

## options

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [IRouterOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/router/irouteroptions) |

## statefulHistory

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

# &#128712; Method(s)

## activate

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## loadUrl

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## deactivate

| Return Type                       |
|-----------------------------------|
| void |

## linkCallback

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**info**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## processNavigations

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**qInstruction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

External API to get viewport by name

## getViewport

| Return Type                       |
|-----------------------------------|
| [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) &#124; null |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Called from the viewport scope custom element

## setClosestScope

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**viewModelOrContainer**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**scope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## getClosestScope

| Return Type                       |
|-----------------------------------|
| [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) &#124; null |

**&#128966; Parameter(s)**

_**viewModelOrElement**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## unsetClosestScope

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**viewModelOrContainer**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Called from the viewport custom element

## connectViewport

| Return Type                       |
|-----------------------------------|
| [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport) |

**&#128966; Parameter(s)**

_**viewport**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Called from the viewport custom element

## disconnectViewport

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**viewport**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Called from the viewport scope custom element

## connectViewportScope

| Return Type                       |
|-----------------------------------|
| [ViewportScope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-scope/viewportscope) |

**&#128966; Parameter(s)**

_**viewportScope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**element**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Called from the viewport scope custom element

## disconnectViewportScope

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**viewportScope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**container**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## allViewports

| Return Type                       |
|-----------------------------------|
| [Viewport](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport/viewport)[] |

**&#128966; Parameter(s)**

_**includeDisabled**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## findScope

| Return Type                       |
|-----------------------------------|
| [Scope](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/scope/scope) |

**&#128966; Parameter(s)**

_**elementOrViewmodelOrviewport**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## goto

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

**&#128966; Parameter(s)**

_**instructions**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## refresh

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## back

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## forward

| Return Type                       |
|-----------------------------------|
| Promise&lt;void&gt; |

## checkActive

| Return Type                       |
|-----------------------------------|
| boolean |

**&#128966; Parameter(s)**

_**instructions**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## setNav

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**routes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**classes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## addNav

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**routes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**classes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## updateNav

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## findNav

| Return Type                       |
|-----------------------------------|
| [Nav](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav/nav) |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## addRoutes

| Return Type                       |
|-----------------------------------|
| [IRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/interfaces/iroute)[] |

**&#128966; Parameter(s)**

_**routes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**context**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## removeRoutes

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**routes**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**context**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## addHooks

| Return Type                       |
|-----------------------------------|
| number[] |

**&#128966; Parameter(s)**

_**hooks**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## addHook

| Return Type                       |
|-----------------------------------|
| number |

**&#128966; Parameter(s)**

_**beforeNavigationHookFunction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## addHook

| Return Type                       |
|-----------------------------------|
| number |

**&#128966; Parameter(s)**

_**transformFromUrlHookFunction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## addHook

| Return Type                       |
|-----------------------------------|
| number |

**&#128966; Parameter(s)**

_**transformToUrlHookFunction**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

## addHook

| Return Type                       |
|-----------------------------------|
| number |

**&#128966; Parameter(s)**

_**hook**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## removeHooks

| Return Type                       |
|-----------------------------------|
| void |

**&#128966; Parameter(s)**

_**hooks**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## createViewportInstruction

| Return Type                       |
|-----------------------------------|
| [ViewportInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/viewport-instruction/viewportinstruction) |

**&#128966; Parameter(s)**

_**component**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**viewport**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**parameters**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**ownsScope**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |

_**nextScopeInstructions**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✔  | ✘ | ✘ | - |