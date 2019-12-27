## &#128366; Summary

Class responsible for handling interactions that should trigger navigation.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HTMLDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/class/dom/htmldom) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**inject**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, static, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**window**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**document**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**options**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isActive**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**handler**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

# &#128712; Method(s)

### &#128366; Summary

Gets the href and a "should handle" recommendation, given an Event.

**Parameter(s)**

| Name  | Description                                       |
| ----- | ------------------------------------------------- |
| event |  The Event to inspect for target anchor and href. |

## getEventInfo

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, static | ✘ | [AnchorEventInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/link-handler/anchoreventinfo) |

**&#128966; Parameter(s)**

_**event**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | MouseEvent | ✘  | ✘ | ✘ | - |

_**win**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Window | ✘  | ✘ | ✘ | - |

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ILinkHandlerOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/link-handler/ilinkhandleroptions) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Finds the closest ancestor that's an anchor element.
Gets a value indicating whether or not an anchor targets the current window.
private static closestAnchor(el: Element): Element | null {
while (el !== null && el !== void 0) {
if (el.tagName === 'A') {
return el;
}
el = el.parentNode as Element;
}
return null;
}
Finds the closest ancestor that's an anchor element.
Gets a value indicating whether or not an anchor targets the current window.

**Parameter(s)**

| Name   | Description                                           |
| ------ | ----------------------------------------------------- |
|        |  The element to search upward from.                   |
| target |  The anchor element whose target should be inspected. |
|        |  The element to search upward from.                   |
| target |  The anchor element whose target should be inspected. |

**Returns**

The link element that is the closest ancestor.

## targetIsThisWindow

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, static | ✘ | boolean |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Element | ✘  | ✘ | ✘ | - |

_**win**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Window | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Activate the instance.

## activate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**options**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ILinkHandlerOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/router/interface/link-handler/ilinkhandleroptions) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Deactivate the instance. Event handlers and other resources should be cleaned up here.

## deactivate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |