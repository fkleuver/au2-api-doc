# IInputElement

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | HTMLInputElement |

# &#128712; Property(ies)

## model

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | unknown |

## $observers

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | ({ [x: string]: PropertyObserver; [x: number]: PropertyObserver; } & { getOrCreate(lifecycle: ILifecycle, flags: LifecycleFlags, obj: IOverrideContext &#124; IBindingContext, key: string): PropertyObserver; } & { model?: [SetterObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/observation/interface/setter-observer/setterobserver) &#124; undefined; value?: [ValueAttributeObserver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime-html/observation/interface/value-attribute-observer/valueattributeobserver) &#124; undefined; }) &#124; undefined |

## matcher

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✔ | typeof defaultMatcher &#124; undefined |