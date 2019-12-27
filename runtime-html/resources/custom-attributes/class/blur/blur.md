| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [ICustomAttributeViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributeviewmodel)&lt;HTMLElement&gt; |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| customAttribute | ✔  |

| Argument(s)                                           |
|-------------------------------------------------------|
| 'blur'  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| INode | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**element**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [INode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/dom/inode) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IDOM | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HTMLDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/class/dom/htmldom) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IScheduler | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**scheduler**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$controller**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**value**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**onBlur**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Used to determine which elements this attribute will be linked with
Interacting with a linked element will not trigger blur for this attribute

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**linkedWith**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Only used when `linkedWith` is a string and searchSubTree is `true`.
Used to determine whether to use querySelector / querySelectorAll to find all interactable elements without triggering blur.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**linkedMultiple**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Only used when linkedWith is a string, or an array containing some strings
During query for finding element to link with:
- `true`: search all descendants
- `false`: search immediate children using for loop

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**searchSubTree**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Only used when linkedWith is a string. or an array containing a string
Determine from which node/ nodes, search for elements

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128966; Decorators(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| bindable | ✔  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**linkingContext**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Manager of this custom attribute to centralize listeners

**Internal**

No need to expose BlurManager

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**manager**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**element**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Method(s)

## afterAttach

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## beforeDetach

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## handleEventTarget

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | EventTarget | ✘  | ✘ | ✘ | - |

## contains

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Element | ✘  | ✘ | ✘ | - |

## triggerBlur

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |