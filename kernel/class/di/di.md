| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✔ | ✔ | ✘ |

# &#128712; Method(s)

## createContainer

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) |

**&#128966; Parameter(s)**

_**params**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | any[] | ✔  | ✔ | ✘ | - |

## getDesignParamtypes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | readonly Key[] &#124; undefined |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

## getAnnotationParamtypes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | readonly Key[] &#124; undefined |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

## getOrCreateAnnotationParamTypes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | Key[] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

## getDependencies

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | Key[] |

**&#128966; Parameter(s)**

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Constructable&lt;{}&gt; &#124; Injectable&lt;{}&gt; | ✘  | ✘ | ✘ | - |

### &#128966; Type Parameter(s)

| Type | Constraint |
| ---- | ---------- |
| K    | Key        |

## createInterface

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IDefaultableInterfaceSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/idefaultableinterfacesymbol)&lt;K&gt; |

**&#128966; Parameter(s)**

_**friendlyName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; undefined | ✔  | ✘ | ✘ | - |

## inject

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | (target: Injectable&lt;{}&gt;, key?: string &#124; number &#124; undefined, descriptor?: number &#124; PropertyDescriptor &#124; undefined) =&gt; void |

**&#128966; Parameter(s)**

_**dependencies**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Key[] | ✔  | ✔ | ✘ | - |

### &#128366; Summary

Registers the `target` class as a transient dependency; each time the dependency is resolved
a new instance will be created.

**Parameter(s)**

| Name   | Description                                                 |
| ------ | ----------------------------------------------------------- |
| target |  The class / constructor function to register as transient. |

**Returns**

The same class, with a static `register` method that takes a container and returns the appropriate resolver.

**Example**

```ts
// On an existing class
class Foo { }
DI.transient(Foo);
// Inline declaration
const Foo = DI.transient(class { });
// Foo is now strongly typed with register
Foo.register(container);
```

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## transient

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | T & RegisterSelf&lt;T&gt; |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T & Partial&lt;RegisterSelf&lt;T&gt;&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

Registers the `target` class as a singleton dependency; the class will only be created once. Each
consecutive time the dependency is resolved, the same instance will be returned.
  
  **Parameter(s)**

| Name   | Description                                                   |
| ------ | ------------------------------------------------------------- |
| target |  The class / constructor function to register as a singleton. |

**Returns**

The same class, with a static `register` method that takes a container and returns the appropriate resolver.
  
  **Example**

```ts
// On an existing class
class Foo { }
DI.singleton(Foo);
// Inline declaration
const Foo = DI.singleton(class { });
// Foo is now strongly typed with register
Foo.register(container);
```

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## singleton

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | T & RegisterSelf&lt;T&gt; |

**&#128966; Parameter(s)**

_**target**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | T & Partial&lt;RegisterSelf&lt;T&gt;&gt; | ✘  | ✘ | ✘ | - |