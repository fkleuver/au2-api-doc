| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | ResourceDefinition&lt;T, [ICustomElementViewModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/lifecycle/icustomelementviewmodel)&lt;INode&gt;, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: [BindingStrategy](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingstrategy) &#124; undefined; readonly hooks?: Readonly&lt;[HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition)&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;, {}, InstanceType&lt;T&gt;&gt; |

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
| ResourceType&lt;T, ICustomElementViewModel&lt;INode&gt; & (T extends Constructable&lt;infer P&gt; ? P : {}), PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**name**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**aliases**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string[] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**key**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**cache**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| number &#124; "*" | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**template**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| unknown | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**instructions**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| readonly (readonly [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[])[] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dependencies**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| readonly Key[] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**injectable**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| InjectableToken&lt;T&gt; &#124; null | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**needsCompile**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**surrogates**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| readonly [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[] | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**bindables**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Record&lt;string, [BindableDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/bindable/bindabledefinition)&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**childrenObservers**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Record&lt;string, [ChildrenDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/templating/class/children/childrendefinition)&lt;INode&gt;&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**containerless**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**isStrictBinding**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**shadowOptions**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| { mode: "open" &#124; "closed"; } &#124; null | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**hasSlots**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| boolean | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**strategy**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [BindingStrategy](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingstrategy) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**hooks**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| Readonly&lt;[HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition)&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**scopeParts**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| string[] | ✘  | ✘ | ✔ |

# &#128712; Method(s)

### &#128966; Type Parameter(s)

| Type | Constraint              |
| ---- | ----------------------- |
| T    | Constructable&lt;{}&gt; |

## create

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;T&gt; |

**&#128966; Parameter(s)**

_**nameOrDef**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

_**Type**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ResourceType&lt;T, ICustomElementViewModel&lt;INode&gt; & (T extends Constructable&lt;infer P&gt; ? P : {}), PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;, InstanceType&lt;T&gt;&gt; &#124; null | ✔  | ✘ | ✘ | null |

## getOrCreate

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt; |

**&#128966; Parameter(s)**

_**partialDefinition**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | void |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |