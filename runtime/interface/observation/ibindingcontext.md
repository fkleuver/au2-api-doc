# IBindingContext

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | - |

# &#128712; Indexer(s)

**&#128966; Return Type**

any

| Key Name        | Key Type                       |
|-----------------|--------------------------------|
| key | string |

# &#128712; Property(ies)

## $synthetic

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | true &#124; undefined |

## $observers

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | IIndexable&lt;{ getOrCreate(lifecycle: ILifecycle, flags: LifecycleFlags, obj: IBindingContext &#124; IOverrideContext, key: string): PropertyObserver; }, PropertyObserver, string &#124; number &#124; symbol&gt; &#124; undefined |

# &#128712; Method(s)

## getObservers

| Return Type                       |
|-----------------------------------|
| IIndexable&lt;{ getOrCreate(lifecycle: ILifecycle, flags: [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags), obj: IBindingContext &#124; IOverrideContext, key: string): PropertyObserver; }, PropertyObserver, string &#124; number &#124; symbol&gt; |

**&#128966; Parameter(s)**

_**flags**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |