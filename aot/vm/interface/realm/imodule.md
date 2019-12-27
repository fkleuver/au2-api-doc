# &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-abstract-module-records

# IModule

| Modifier(s)                            | Extends                                    |
|----------------------------------------|--------------------------------------------|
| export | [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

# &#128712; Property(ies)

### &#128366; Summary

This field is never used. Its only purpose is to help TS distinguish this interface from others.

## '<IModule>'

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | unknown |

## isAbrupt

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | false |

## '[[Environment]]'

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [$Undefined](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/undefined/usdundefined) &#124; [$ModuleEnvRec](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/environment-record/usdmoduleenvrec) |

## '[[Namespace]]'

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [$Undefined](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/undefined/usdundefined) &#124; [$NamespaceExoticObject](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/exotics/class/namespace/usdnamespaceexoticobject) |

## '[[HostDefined]]'

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | any |

## realm

| Optional                           | Type                         |
|:----------------------------------:|------------------------------|
| ✘ | [Realm](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/realm) |

# &#128712; Method(s)

## ResolveExport

| Return Type                       |
|-----------------------------------|
| [$Null](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/null/usdnull) &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [ResolvedBindingRecord](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/resolvedbindingrecord) &#124; [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;"ambiguous"&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**exportName**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**resolveSet**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## GetExportedNames

| Return Type                       |
|-----------------------------------|
| [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [$List](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/list/usdlist)&lt;[$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt;&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

_**exportStarSet**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |

## Instantiate

| Return Type                       |
|-----------------------------------|
| [$Undefined](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/undefined/usdundefined) &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ✘  | ✘ | ✘ | - |