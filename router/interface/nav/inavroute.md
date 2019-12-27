# INavRoute

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Property(ies)

## route

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; Constructable&lt;{}&gt; &#124; RouteableComponentType&lt;Constructable&lt;{}&gt;&gt; &#124; IRouteableComponent&lt;INode&gt; &#124; IViewportInstruction &#124; ViewportInstruction &#124; NavigationInstruction[] &#124; undefined |

## execute

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ((route: [NavRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav-route/navroute)) =&gt; void) &#124; undefined |

## condition

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; ((route: [NavRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav-route/navroute)) =&gt; boolean) &#124; undefined |

## consideredActive

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; Constructable&lt;{}&gt; &#124; RouteableComponentType&lt;Constructable&lt;{}&gt;&gt; &#124; IRouteableComponent&lt;INode&gt; &#124; IViewportInstruction &#124; ViewportInstruction &#124; NavigationInstruction[] &#124; ((route: [NavRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/nav-route/navroute)) =&gt; boolean) &#124; undefined |

## compareParameters

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | boolean &#124; undefined |

## link

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | string &#124; undefined |

## title

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | string |

## children

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | [INavRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/nav/inavroute)[] &#124; undefined |

## meta

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | Record&lt;string, unknown&gt; &#124; undefined |