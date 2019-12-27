| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IServiceHost](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/interface/service-host/iservicehost) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**container**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**logger**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) | ✔  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**fs**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IFileSystem](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifilesystem) | ✔  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**_jsdom**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**agent**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**compilerOptionsCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**moduleCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**scriptCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

# &#128712; Get Accessor(s)

## jsdom

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## loadEntryFile

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, async | ✘ | Promise&lt;[$ESModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesmodule)&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**dir**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## loadSpecificFile

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, async | ✘ | Promise&lt;$$ESModuleOrScript&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**file**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✘ | - |

_**mode**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | "script" &#124; "module" | ✘  | ✘ | ✘ | - |

## executeEntryFile

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;$Any&gt; |

**&#128966; Parameter(s)**

_**dir**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## executeSpecificFile

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;$Any&gt; |

**&#128966; Parameter(s)**

_**file**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✘ | - |

_**mode**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | "script" &#124; "module" | ✘  | ✘ | ✘ | - |

## executeProvider

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | Promise&lt;$Any&gt; |

**&#128966; Parameter(s)**

_**provider**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ISourceFileProvider](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/variable/agent/isourcefileprovider) | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-hostresolveimportedmodule

## ResolveImportedModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [IModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/interface/realm/imodule) |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**referencingModule**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$ESModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesmodule) | ✘  | ✘ | ✘ | - |

_**$specifier**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt; | ✘  | ✘ | ✘ | - |

## dispose

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**this**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Writable&lt;Partial&lt;[ServiceHost](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/class/service-host/servicehost)&gt;&gt; | ✘  | ✘ | ✘ | - |

## loadEntryPackage

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Promise&lt;[NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage)&gt; |

**&#128966; Parameter(s)**

_**dir**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## getHTMLModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [$DocumentFragment](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usddocumentfragment) |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**file**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✘ | - |

_**pkg**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) | ✘  | ✘ | ✘ | - |

## getESScript

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [$ESScript](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesscript) |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**file**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✘ | - |

## getESModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [$ESModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesmodule) |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**file**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IFile](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifile) | ✘  | ✘ | ✘ | - |

_**pkg**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) &#124; null | ✘  | ✘ | ✘ | - |

## getCompilerOptions

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [$CompilerOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/usdcompileroptions) |

**&#128966; Parameter(s)**

_**path**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

_**pkg**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) &#124; null | ✘  | ✘ | ✘ | - |