## &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-code-realms

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [IDisposable](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/interfaces/idisposable) |

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
| [ILogger](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/logger/ilogger) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**PromiseJobs**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [JobQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/job/jobqueue)&lt;Job&lt;$$ESModuleOrScript&gt;&gt; | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**timeout**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**contextId**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**stack**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[Intrinsics]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[GlobalObject]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[GlobalEnv]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**'[[TemplateMap]]'**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| public | ✘ | - | - |

# &#128712; Get Accessor(s)

## isAbrupt

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-createrealm
8.2.1 CreateRealm ( )

## Create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [Realm](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/realm) |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

_**promiseJobs**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [JobQueue](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/job/jobqueue)&lt;Job&lt;$$ESModuleOrScript&gt;&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-getactivescriptormodule
8.3.1 GetActiveScriptOrModule ( )

## GetActiveScriptOrModule

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $$ESModuleOrScript |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-resolvebinding
8.3.2 ResolveBinding ( name [ , env ] )

## ResolveBinding

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [$Reference](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/reference/usdreference) |

**&#128966; Parameter(s)**

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt; | ✘  | ✘ | ✘ | - |

_**env**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | $DeclarativeEnvRec &#124; $ObjectEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec &#124; undefined | ✔  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-getthisenvironment
8.3.3 GetThisEnvironment ( )

## GetThisEnvironment

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [$FunctionEnvRec](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/environment-record/usdfunctionenvrec) &#124; [$GlobalEnvRec](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/environment-record/usdglobalenvrec) &#124; [$ModuleEnvRec](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/environment-record/usdmoduleenvrec) |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-resolvethisbinding
8.3.4 ResolveThisBinding ( )

## ResolveThisBinding

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $AnyNonEmpty |

### &#128366; Summary

#region helper methods

## GetCurrentLexicalEnvironment

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | $EnvRec |

## SetCurrentLexicalEnvironment

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**envRec**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | $EnvRec | ✘  | ✘ | ✘ | - |

### &#128366; Summary

#endregion

## dispose

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**this**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Writable&lt;Partial&lt;[Realm](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/class/realm/realm)&gt;&gt; | ✘  | ✘ | ✘ | - |

### &#128366; Summary

http:www.ecma-international.org/ecma-262/#sec-getidentifierreference
8.1.2.1 GetIdentifierReference ( lex , name , strict )

## GetIdentifierReference

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [$Error](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/error/usderror)&lt;Error, string&gt; &#124; [$Reference](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/reference/usdreference) |

**&#128966; Parameter(s)**

_**lex**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$Null](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/null/usdnull) &#124; $DeclarativeEnvRec &#124; $ObjectEnvRec &#124; $FunctionEnvRec &#124; $GlobalEnvRec &#124; $ModuleEnvRec | ✘  | ✘ | ✘ | - |

_**name**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$String](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/string/usdstring)&lt;string&gt; | ✘  | ✘ | ✘ | - |

_**strict**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [$Boolean](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/vm/types/class/boolean/usdboolean)&lt;boolean&gt; | ✘  | ✘ | ✘ | - |