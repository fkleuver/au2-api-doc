## &#128366; Summary

Class that parses route patterns and matches path strings.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**rootState**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**names**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**routes**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Method(s)

### &#128366; Summary

Parse a route pattern and add it to the collection of recognized routes.

**Parameter(s)**

| Name  | Description        |
| ----- | ------------------ |
| route |  The route to add. |

## add

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [State](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/route-recognizer/state) &#124; undefined |

**&#128966; Parameter(s)**

_**route**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ConfigurableRoute](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/configurableroute) &#124; ConfigurableRoute[] | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Retrieve a RouteGenerator for a route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

The RouteGenerator for that route.

## getRoute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [RouteGenerator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/route-recognizer/routegenerator) |

**&#128966; Parameter(s)**

_**nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; [RouteHandler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/routehandler) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Retrieve the handlers registered for the route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

The handlers.

## handlersFor

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [HandlerEntry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/class/route-recognizer/handlerentry)[] |

**&#128966; Parameter(s)**

_**nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; [RouteHandler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/routehandler) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Check if this RouteRecognizer recognizes a route by name or RouteConfig (RouteHandler).

**Parameter(s)**

| Name        | Description                                   |
| ----------- | --------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object. |

**Returns**

True if the named route is recognized.

## hasRoute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; [RouteHandler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/routehandler) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Generate a path and query string from a route name or RouteConfig (RouteHandler) and params object.

**Parameter(s)**

| Name        | Description                                                                                                                        |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| nameOrRoute |  The name of the route or RouteConfig object.                                                                                      |
| params      |  The route params to use when populating the pattern. Properties not required by the pattern will be appended to the query string. |

**Returns**

The generated absolute path and query string.

## generate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | string |

**&#128966; Parameter(s)**

_**nameOrRoute**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; [RouteHandler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/routehandler) | ✘  | ✘ | ✘ | - |

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | object &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

Match a path string against registered route patterns.

**Parameter(s)**

| Name | Description                    |
| ---- | ------------------------------ |
| path |  The path to attempt to match. |

**Returns**

Array of objects containing `handler`, `params`, and
`isDynamic` values for the matched route(s), or undefined if no match
was found.

## recognize

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [RecognizeResults](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/route-recognizer/recognizeresults) |

**&#128966; Parameter(s)**

_**path**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |