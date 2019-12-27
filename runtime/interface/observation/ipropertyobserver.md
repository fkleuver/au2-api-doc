# &#128366; Summary

Describes a complete property observer with an accessor, change tracking fields, normal and batched subscribers

# IPropertyObserver

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IAccessor](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/iaccessor)&lt;TObj[TProp]&gt;, [IPropertyChangeTracker](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/ipropertychangetracker)&lt;TObj, TProp, unknown&gt;, [ISubscriberCollection](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/isubscribercollection), [IBatchable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/observation/ibatchable) |

# &#128712; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| TObj | object     |

| Type  | Constraint |
| ----- | ---------- |
| TProp | keyof TObj |

# &#128712; Property(ies)

## inBatch

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## observing

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | boolean |

## persistentFlags

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [LifecycleFlags](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/lifecycleflags) |