| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**config**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IRegistry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistry) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**wnd**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Window | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Scheduler**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Constructable&lt;[IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler)&gt; | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**UIEventType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (type: string, eventInitDict?: UIEventInit &#124; undefined): UIEvent; prototype: UIEvent; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**EventType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (type: string, eventInitDict?: EventInit &#124; undefined): Event; prototype: Event; readonly AT&#95;TARGET: number; readonly BUBBLING&#95;PHASE: number; readonly CAPTURING&#95;PHASE: number; readonly NONE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**CustomEventType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new &lt;T&gt;(typeArg: string, eventInitDict?: CustomEventInit&lt;T&gt; &#124; undefined): CustomEvent&lt;T&gt;; prototype: CustomEvent&lt;any&gt;; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**NodeType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): Node; prototype: Node; readonly ATTRIBUTE&#95;NODE: number; readonly CDATA&#95;SECTION&#95;NODE: number; readonly COMMENT&#95;NODE: number; readonly DOCUMENT&#95;FRAGMENT&#95;NODE: number; readonly DOCUMENT&#95;NODE: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINED&#95;BY: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINS: number; readonly DOCUMENT&#95;POSITION&#95;DISCONNECTED: number; readonly DOCUMENT&#95;POSITION&#95;FOLLOWING: number; readonly DOCUMENT&#95;POSITION&#95;IMPLEMENTATION&#95;SPECIFIC: number; readonly DOCUMENT&#95;POSITION&#95;PRECEDING: number; readonly DOCUMENT&#95;TYPE&#95;NODE: number; readonly ELEMENT&#95;NODE: number; readonly ENTITY&#95;NODE: number; readonly ENTITY&#95;REFERENCE&#95;NODE: number; readonly NOTATION&#95;NODE: number; readonly PROCESSING&#95;INSTRUCTION&#95;NODE: number; readonly TEXT&#95;NODE: number; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ElementType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): Element; prototype: Element; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**HTMLElementType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): HTMLElement; prototype: HTMLElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**HTMLDivElementType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): HTMLDivElement; prototype: HTMLDivElement; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**TextType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (data?: string &#124; undefined): Text; prototype: Text; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**CommentType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (data?: string &#124; undefined): Comment; prototype: Comment; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**DOMParserType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): DOMParser; prototype: DOMParser; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**CSSStyleSheetType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): CSSStyleSheet; prototype: CSSStyleSheet; } | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ShadowRootType**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { new (): ShadowRoot; prototype: ShadowRoot; } | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**wnd**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**doc**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**UIEvent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Event**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**CustomEvent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Node**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Element**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**HTMLElement**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**HTMLDivElement**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Text**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Comment**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**DOMParser**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**config**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_container**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_scheduler**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_templateCompiler**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_observerLocator**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_lifecycle**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_renderer**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_projectorLocator**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_domParser**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✔ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Scheduler**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Get Accessor(s)

## container

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## scheduler

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## templateCompiler

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## observerLocator

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## lifecycle

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## renderer

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## projectorLocator

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## domParser

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [HTMLTestContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/html-test-context/htmltestcontext) |

**&#128966; Parameter(s)**

_**config**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IRegistry](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iregistry) | ✘  | ✘ | ✘ | - |

_**wnd**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Window | ✘  | ✘ | ✘ | - |

_**Scheduler**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;[IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler)&gt; | ✘  | ✘ | ✘ | - |

_**UIEventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (type: string, eventInitDict?: UIEventInit &#124; undefined): UIEvent; prototype: UIEvent; } | ✘  | ✘ | ✘ | - |

_**EventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (type: string, eventInitDict?: EventInit &#124; undefined): Event; prototype: Event; readonly AT&#95;TARGET: number; readonly BUBBLING&#95;PHASE: number; readonly CAPTURING&#95;PHASE: number; readonly NONE: number; } | ✘  | ✘ | ✘ | - |

_**CustomEventType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new &lt;T&gt;(typeArg: string, eventInitDict?: CustomEventInit&lt;T&gt; &#124; undefined): CustomEvent&lt;T&gt;; prototype: CustomEvent&lt;any&gt;; } | ✘  | ✘ | ✘ | - |

_**NodeType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): Node; prototype: Node; readonly ATTRIBUTE&#95;NODE: number; readonly CDATA&#95;SECTION&#95;NODE: number; readonly COMMENT&#95;NODE: number; readonly DOCUMENT&#95;FRAGMENT&#95;NODE: number; readonly DOCUMENT&#95;NODE: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINED&#95;BY: number; readonly DOCUMENT&#95;POSITION&#95;CONTAINS: number; readonly DOCUMENT&#95;POSITION&#95;DISCONNECTED: number; readonly DOCUMENT&#95;POSITION&#95;FOLLOWING: number; readonly DOCUMENT&#95;POSITION&#95;IMPLEMENTATION&#95;SPECIFIC: number; readonly DOCUMENT&#95;POSITION&#95;PRECEDING: number; readonly DOCUMENT&#95;TYPE&#95;NODE: number; readonly ELEMENT&#95;NODE: number; readonly ENTITY&#95;NODE: number; readonly ENTITY&#95;REFERENCE&#95;NODE: number; readonly NOTATION&#95;NODE: number; readonly PROCESSING&#95;INSTRUCTION&#95;NODE: number; readonly TEXT&#95;NODE: number; } | ✘  | ✘ | ✘ | - |

_**ElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): Element; prototype: Element; } | ✘  | ✘ | ✘ | - |

_**HTMLElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): HTMLElement; prototype: HTMLElement; } | ✘  | ✘ | ✘ | - |

_**HTMLDivElementType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): HTMLDivElement; prototype: HTMLDivElement; } | ✘  | ✘ | ✘ | - |

_**TextType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (data?: string &#124; undefined): Text; prototype: Text; } | ✘  | ✘ | ✘ | - |

_**CommentType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (data?: string &#124; undefined): Comment; prototype: Comment; } | ✘  | ✘ | ✘ | - |

_**DOMParserType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): DOMParser; prototype: DOMParser; } | ✘  | ✘ | ✘ | - |

_**CSSStyleSheetType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): CSSStyleSheet; prototype: CSSStyleSheet; } | ✘  | ✘ | ✘ | - |

_**ShadowRootType**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { new (): ShadowRoot; prototype: ShadowRoot; } | ✘  | ✘ | ✘ | - |

## createElementFromMarkup

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | HTMLElement |

**&#128966; Parameter(s)**

_**markup**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## createElement

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | HTMLElement |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## createAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Attr |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |