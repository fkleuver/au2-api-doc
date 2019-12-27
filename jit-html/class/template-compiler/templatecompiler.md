## &#128366; Summary

Default (runtime-agnostic) implementation for `ITemplateCompiler`.

**Internal**

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | [ITemplateCompiler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/renderer/itemplatecompiler) |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| ITemplateElementFactory | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**factory**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ITemplateElementFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/template-element-factory/itemplateelementfactory)&lt;INode&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IAttributeParser | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**attrParser**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IAttributeParser](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/interface/attribute-parser/iattributeparser) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IExpressionParser | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**exprParser**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IExpressionParser](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/binding/interface/expression-parser/iexpressionparser) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Decorator(s)**

| Name       | Decorator Factory                        |
|------------|:----------------------------------------:|
| IAttrSyntaxTransformer | ✘  |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**attrSyntaxModifier**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IAttrSyntaxTransformer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/attribute-syntax-transformer/iattrsyntaxtransformer) | ✘  | ✘ | ✔ |

## &#128712; Property(ies)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**compilation**_

| Modifier(s)                               | Optional                           | Type                        | Initializer                       |
|-------------------------------------------|:----------------------------------:|-----------------------------|-----------------------------------|
| private | ✘ | - | - |

# &#128712; Get Accessor(s)

## name

| Modifier(s)                              | Return Type                       |
|------------------------------------------|-----------------------------------|
| public | - |

# &#128712; Method(s)

## register

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public, static | ✘ | [IResolver](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/iresolver)&lt;[ITemplateCompiler](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/interface/renderer/itemplatecompiler)&gt; |

**&#128966; Parameter(s)**

_**container**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## compile

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [CustomElementDefinition](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/resources/class/custom-element/customelementdefinition)&lt;Constructable&lt;{}&gt;&gt; |

**&#128966; Parameter(s)**

_**partialDefinition**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly ITargetedInstruction[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt; | ✘  | ✘ | ✘ | - |

_**context**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [IContainer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/kernel/interface/di/icontainer) | ✘  | ✘ | ✘ | - |

## compileChildNodes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**parent**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**instructionRows**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[][] | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |

## compileCustomElement

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) | ✘  | ✘ | ✘ | - |

_**instructionRows**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[][] | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |

## compilePlainElement

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) | ✘  | ✘ | ✘ | - |

_**instructionRows**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[][] | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |

## compileParentNode

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ParentNodeSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**instructionRows**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[][] | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |

## compileTemplateController

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [TemplateControllerSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/templatecontrollersymbol) | ✘  | ✘ | ✘ | - |

_**instructionRows**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[][] | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |

## compileBindings

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | HTMLAttributeInstruction[] |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | SymbolWithBindings&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

## compileBinding

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | HTMLAttributeInstruction |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [BindingSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/semantic-model/bindingsymbol) | ✘  | ✘ | ✘ | - |

## compileAttributes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | HTMLAttributeInstruction[] |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**offset**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | number | ✘  | ✘ | ✘ | - |

## compileCustomAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | HTMLAttributeInstruction |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomAttributeSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/semantic-model/customattributesymbol) | ✘  | ✘ | ✘ | - |

## compilePlainAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | HTMLAttributeInstruction |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainAttributeSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/semantic-model/plainattributesymbol) | ✘  | ✘ | ✘ | - |

_**isOnSurrogate**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | boolean | ✘  | ✘ | ✘ | - |

### &#128366; Summary

private compileAttribute(symbol: IAttributeSymbol): HTMLAttributeInstruction {
any attribute on a custom element (which is not a bindable) or a plain element
if (symbol.flags & SymbolFlags.isCustomAttribute) {
return this.compileCustomAttribute(symbol as CustomAttributeSymbol);
} else {
return this.compilePlainAttribute(symbol as PlainAttributeSymbol);
}
}

## compileParts

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | Record&lt;string, PartialResourceDefinition&lt;{ readonly cache?: number &#124; "*" &#124; undefined; readonly template?: unknown; readonly instructions?: readonly (readonly [ITargetedInstruction](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/definitions/itargetedinstruction)[])[] &#124; undefined; readonly dependencies?: readonly Key[] &#124; undefined; readonly injectable?: InjectableToken&lt;any&gt; &#124; null &#124; undefined; readonly needsCompile?: boolean &#124; undefined; readonly surrogates?: readonly ITargetedInstruction[] &#124; undefined; readonly bindables?: readonly string[] &#124; Record&lt;string, PartialBindableDefinition&gt; &#124; undefined; readonly childrenObservers?: Record&lt;string, PartialChildrenDefinition&lt;INode&gt;&gt; &#124; undefined; readonly containerless?: boolean &#124; undefined; readonly isStrictBinding?: boolean &#124; undefined; readonly shadowOptions?: { mode: "open" &#124; "closed"; } &#124; null &#124; undefined; readonly hasSlots?: boolean &#124; undefined; readonly strategy?: BindingStrategy &#124; undefined; readonly hooks?: Readonly&lt;HooksDefinition&gt; &#124; undefined; readonly scopeParts?: readonly string[] &#124; undefined; }&gt;&gt; |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) | ✘  | ✘ | ✘ | - |

_**scopeParts**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string[] | ✘  | ✘ | ✘ | - |