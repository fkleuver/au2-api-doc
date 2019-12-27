# PartialCustomAttributeDefinition

| Modifier(s)                            | Type                     |
|----------------------------------------|--------------------------|
| export | PartialResourceDefinition&lt;{ readonly default[BindingMode](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingmode)?: BindingMode &#124; undefined; readonly isTemplateController?: boolean &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly strategy?: [BindingStrategy](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/enum/flags/bindingstrategy) &#124; undefined; readonly hooks?: [HooksDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/class/definitions/hooksdefinition) &#124; undefined; }&gt; |

# &#128712; Initializer

PartialResourceDefinition<{
readonly defaultBindingMode?: BindingMode;
readonly isTemplateController?: boolean;
readonly bindables?: Record<string, PartialBindableDefinition> | readonly string[];
readonly strategy?: BindingStrategy;
readonly hooks?: HooksDefinition;
}>