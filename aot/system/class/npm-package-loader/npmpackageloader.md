| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

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

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**fs**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IFileSystem](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/interface/interfaces/ifilesystem) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkgCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkgPromiseCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkgResolveCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**pkgResolvePromiseCache**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private, readonly | ✘ | - | - |

# &#128712; Get Accessor(s)

## inject

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public, static | - |

# &#128712; Method(s)

## loadEntryPackage

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, async | ✘ | Promise&lt;[NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage)&gt; |

**&#128966; Parameter(s)**

_**projectDir**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## getCachedPackage

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage) |

**&#128966; Parameter(s)**

_**refName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## loadPackageCore

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, async | ✘ | Promise&lt;[NPMPackage](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackage)&gt; |

**&#128966; Parameter(s)**

_**dir**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; null | ✘  | ✘ | ✘ | - |

_**issuer**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackageDependency](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackagedependency) &#124; null | ✘  | ✘ | ✘ | - |

## resolvePackagePath

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, async | ✘ | Promise&lt;string&gt; |

**&#128966; Parameter(s)**

_**dep**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackageDependency](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackagedependency) | ✘  | ✘ | ✘ | - |

## resolvePackagePathCore

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private, async | ✘ | Promise&lt;string&gt; |

**&#128966; Parameter(s)**

_**dep**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [NPMPackageDependency](https://hamedfathi.gitbook.io/aurelia-2-doc-api/aot/system/class/npm-package-loader/npmpackagedependency) | ✘  | ✘ | ✘ | - |