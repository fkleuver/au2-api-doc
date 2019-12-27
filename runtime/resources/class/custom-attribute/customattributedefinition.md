| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | ResourceDefinition&lt;T, [ICustomAttributeViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomattributeviewmodel)&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly default[BindingMode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingmode)?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: [BindingStrategy](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingstrategy) &#124; undefined; readonly hooks?: [HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition) &#124; undefined; }&gt;, {}, InstanceType&lt;T&gt;&gt; |

## &#128712; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**Type**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| ResourceType&lt;T, ICustomAttributeViewModel&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**aliases**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| readonly string[] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**key**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**defaultBindingMode**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [BindingMode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingmode) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isTemplateController**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindables**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Record&lt;string, [BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**strategy**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [BindingStrategy](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingstrategy) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**hooks**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition) | ✘  | ✘ | ✔ |

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [CustomAttributeDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-attribute/customattributedefinition)&lt;T&gt; |

**&#128966; Parameter(s)**

_**nameOrDef**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ResourceType&lt;T, ICustomAttributeViewModel&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly defaultBindingMode?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: HooksDefinition &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; | ✘  | ✘ | ✘ | - |

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |