## &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-abstract-module-records
http:www.ecma-international.org/ecma-262/#sec-cyclic-module-records
http:www.ecma-international.org/ecma-262/#sec-source-text-module-records

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
| SourceFile | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**realm**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [Realm](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/realm) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkg**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) &#124; null | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**moduleResolver**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IModuleResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/interface/service-host/imoduleresolver) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**compilerOptions**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [$CompilerOptions](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/usdcompileroptions) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'<IModule>'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**disposed**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**path**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**mos**_

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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**$statements**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**DirectivePrologue**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

Temporary property for testing purposes

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ExecutionResult**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-exportedbindings
15.2.1.5 Static Semantics: ExportedBindings

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ExportedBindings**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-exportednames
15.2.1.6 Static Semantics: ExportedNames

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ExportedNames**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-exportentries
15.2.1.7 Static Semantics: ExportEntries

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ExportEntries**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-importentries
15.2.1.8 Static Semantics: ImportEntries

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ImportEntries**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-importedlocalnames
15.2.1.9 Static Semantics: ImportedLocalNames ( importEntries )

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ImportedLocalNames**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-modulerequests
15.2.1.10 Static Semantics: ModuleRequests

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**ModuleRequests**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-lexicallyscopeddeclarations
15.2.1.12 Static Semantics: LexicallyScopedDeclarations

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**LexicallyScopedDeclarations**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **&#128366; Summary**

http:www.ecma-international.org/ecma-262/#sec-module-semantics-static-semantics-varscopeddeclarations
15.2.1.14 Static Semantics: VarScopedDeclarations

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**VarScopedDeclarations**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**TypeDeclarations**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**IsType**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Status**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**DFSIndex**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**DFSAncestorIndex**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**RequestedModules**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**LocalExportEntries**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**IndirectExportEntries**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**StarExportEntries**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

# &#128712; Get Accessor(s)

## isAbrupt

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## $kind

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## isNull

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## isScript

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

## isModule

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-moduledeclarationinstantiation
15.2.1.16.1 Instantiate ( ) Concrete Method

## Instantiate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Undefined](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/undefined/usdundefined) &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-source-text-module-record-initialize-environment
15.2.1.17.4 InitializeEnvironment ( ) Concrete Method

## InitializeEnvironment

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $Any |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-getexportednames
15.2.1.17.2 GetExportedNames ( exportStarSet ) Concrete Method

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

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-resolveexport
15.2.1.17.3 ResolveExport ( exportName , resolveSet ) Concrete Method

## ResolveExport

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Null](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/null/usdnull) &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [ResolvedBindingRecord](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/resolvedbindingrecord) &#124; [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;"ambiguous"&gt; |

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

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-moduleevaluation
15.2.1.16.2 Evaluate ( ) Concrete Method

## EvaluateModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $Any |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-innermoduleevaluation
15.2.1.16.2.1 InnerModuleEvaluation ( module , stack , idx )

## EvaluateModuleInner

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Number](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/number/usdnumber)&lt;number&gt; &#124; [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

_**stack**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$ESModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesmodule)[] | ✘  | ✘ | ✘ | - |

_**idx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-source-text-module-record-execute-module
15.2.1.17.5 ExecuteModule ( ) Concrete Method

## ExecuteModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $Any |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-module-semantics-runtime-semantics-evaluation
15.2.1.21 Runtime Semantics: Evaluation

## Evaluate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $Any |

**&#128966; Parameter(s)**

_**ctx**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ExecutionContext](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/executioncontext)&lt;$EnvRec, $DeclarativeEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec&gt; | ✘  | ✘ | ✘ | - |

## dispose

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**this**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Writable&lt;Partial&lt;[$ESModule](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/ast/class/modules/usdesmodule)&gt;&gt; | ✘  | ✘ | ✘ | - |