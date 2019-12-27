# createFixture

| Modifier(s)                            | Return Type                    | Generator                        | Overload                         | Implementation                        |
|----------------------------------------|--------------------------------|:--------------------------------:|:--------------------------------:|:-------------------------------------:|
| export | { startPromise: Promise&lt;unknown&gt;; ctx: [HTMLTestContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/html-test-context/htmltestcontext); host: Element &#124; null; container: [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer); lifecycle: [ILifecycle](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ilifecycle); scheduler: [IScheduler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/scheduler/ischeduler); testHost: HTMLDivElement; appHost: HTMLElement; au: [Aurelia](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/aurelia/aurelia)&lt;INode&gt;; component: ICustomElementViewModel&lt;INode&gt; & T; observerLocator: [IObserverLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/observer-locator/iobserverlocator); start: () =&gt; Promise&lt;void&gt;; tearDown: () =&gt; Promise&lt;void&gt;; } | ✘ | ✘  | ✔ |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| T    | -          |

## &#128966; Parameter(s)

_**template**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; Node | ✘  | ✘ | ✘ | - |

_**$class**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;T&gt; &#124; undefined | ✔  | ✘ | ✘ | - |

_**registrations**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | any[] | ✔  | ✘ | ✘ | [] |

_**autoStart**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✔  | ✘ | ✘ | true |

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [HTMLTestContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/testing/class/html-test-context/htmltestcontext) | ✔  | ✘ | ✘ | TestContext.createHTMLTestContext() |