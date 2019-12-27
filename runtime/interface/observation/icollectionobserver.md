# &#128366; Summary

An observer that tracks collection mutations and notifies subscribers (either directly or in batches)

# ICollectionObserver

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [ICollectionChangeTracker](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionchangetracker)&lt;CollectionKindToType&lt;T&gt;&gt;, [ICollectionSubscriberCollection](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionsubscribercollection), [IBatchable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/ibatchable) |

# &#128712; Type Parameter(s)

| Type | Constraint                                                                                                |
| ---- | --------------------------------------------------------------------------------------------------------- |
| T    | [CollectionKind](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/observation/collectionkind) |

# &#128712; Property(ies)

## inBatch

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## lifecycle

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [ILifecycle](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/ilifecycle) |

## persistentFlags

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) |

## collection

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | ObservedCollectionKindToType&lt;T&gt; |

## lengthObserver

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | T extends CollectionKind.array ? [ICollectionLengthObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionlengthobserver) : [ICollectionSizeObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionsizeobserver) |

# &#128712; Method(s)

## getLengthObserver

| Return Type                       |
|-----------------------------------|
| T extends CollectionKind.array ? [ICollectionLengthObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionlengthobserver) : [ICollectionSizeObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/icollectionsizeobserver) |

## notify

| Return Type                       |
|-----------------------------------|
| void |