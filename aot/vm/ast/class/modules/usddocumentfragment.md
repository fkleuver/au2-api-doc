| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [I$Node](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/interface/&#95;shared/iusdnode)&lt;object&gt;, [IModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/interface/realm/imodule) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**logger**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$file**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**node**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| DocumentFragment | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**realm**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [Realm](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/realm) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkg**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) &#124; null | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'<IModule>'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**documentFragment**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**parent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ctx**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**depth**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**path**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[Environment]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[Namespace]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[HostDefined]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Get Accessor(s)

## isNull

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## isAbrupt

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## ResolveExport

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Null](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/null/usdnull) &#124; [ResolvedBindingRecord](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/resolvedbindingrecord) &#124; [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;"ambiguous"&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**exportName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt; | ✘  | ✘ | ✘ | - |

_**resolveSet**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ResolveSet](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/resolveset) | ✘  | ✘ | ✘ | - |

## GetExportedNames

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [$List](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/list/usdlist)&lt;[$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt;&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**exportStarSet**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Set&lt;[IModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/interface/realm/imodule)&gt; | ✘  | ✘ | ✘ | - |

## Instantiate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Undefined](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/undefined/usdundefined) &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

## dispose

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |