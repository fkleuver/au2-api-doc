## &#128366; Summary

Used when there is no setter, and the getter is dependent on other properties of the object;
Used when there is a setter but the value of the getter can change based on properties set outside of the setter.

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [GetterObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/computed-observer/getterobserver) |

## &#128712; Decorators(s)

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| subscriberCollection | ✔  |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**flags**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) | ✘  | ✘ | ✘ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**overrides**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ComputedOverrides](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/computed-observer/computedoverrides) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**obj**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| IObservable&lt;{}&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**propertyKey**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**descriptor**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| PropertyDescriptor | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**observerLocator**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IObserverLocator](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/observer-locator/iobserverlocator) | ✘  | ✘ | ✘ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**currentValue**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**oldValue**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**proxy**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**propertyDeps**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**collectionDeps**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**subscriberCount**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isCollecting**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Method(s)

## addPropertyDep

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**subscribable**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISubscribable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/isubscribable) | ✘  | ✘ | ✘ | - |

## addCollectionDep

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**subscribable**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ICollectionSubscribable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionsubscribable) | ✘  | ✘ | ✘ | - |

## getValue

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | unknown |

## subscribe

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**subscriber**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISubscriber](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/isubscriber)&lt;unknown&gt; | ✘  | ✘ | ✘ | - |

## unsubscribe

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**subscriber**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISubscriber](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/isubscriber)&lt;unknown&gt; | ✘  | ✘ | ✘ | - |

## handleChange

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## handleCollectionChange

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

## getValueAndCollectDependencies

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | unknown |

**&#128966; Parameter(s)**

_**requireCollect**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |

## doNotCollect

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | boolean |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IBindingContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/ibindingcontext) &#124; IObservable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

_**key**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; number &#124; symbol | ✘  | ✘ | ✘ | - |

_**receiver**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | unknown | ✔  | ✘ | ✘ | - |

## unsubscribeAllDependencies

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |