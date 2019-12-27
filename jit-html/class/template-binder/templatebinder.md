## &#128366; Summary

TemplateBinder. Todo: describe goal of this class

| Modifier(s)                            | Extends                      | Implements                                    |
|----------------------------------------|------------------------------|-----------------------------------------------|
| export | - | - |

## &#128712; Constructor(s)

| Parameter-less                         | Implementation                          | Overload                          |
|:--------------------------------------:|:---------------------------------------:|:---------------------------------:|
| ✘ | ✔ | ✘ |

&nbsp;&nbsp; **&#128966; Parameter(s)**

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**dom**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IDOM](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/variable/dom/idom)&lt;INode&gt; | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**resources**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [ResourceModel](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/resourcemodel) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**attrParser**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IAttributeParser](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/interface/attribute-parser/iattributeparser) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**exprParser**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IExpressionParser](https://hamedfathi.gitbook.io/aurelia-2-doc-api/runtime/binding/interface/expression-parser/iexpressionparser) | ✘  | ✘ | ✔ |

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; _**attrSyntaxTransformer**_

| Type                        | Optional                           | Rest                          | Parameter Property                          |
|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|
| [IAttrSyntaxTransformer](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/attribute-syntax-transformer/iattrsyntaxtransformer) | ✘  | ✘ | ✔ |

# &#128712; Method(s)

## bind

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| public | ✘ | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | HTMLTemplateElement | ✘  | ✘ | ✘ | - |

## bindManifest

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**parentManifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | HTMLTemplateElement &#124; HTMLElement | ✘  | ✘ | ✘ | - |

_**surrogate**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**manifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**parentManifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**partName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; null | ✘  | ✘ | ✘ | - |

## bindLetElement

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**parentManifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | HTMLElement | ✘  | ✘ | ✘ | - |

## bindAttributes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | HTMLTemplateElement &#124; HTMLElement | ✘  | ✘ | ✘ | - |

_**parentManifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**surrogate**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**manifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**parentManifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**partName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; null | ✘  | ✘ | ✘ | - |

### &#128366; Summary

TODO: refactor to use render priority slots (this logic shouldn't be in the template binder)

## ensureAttributeOrder

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

## bindChildNodes

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**node**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | HTMLTemplateElement &#124; HTMLElement | ✘  | ✘ | ✘ | - |

_**surrogate**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**manifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**parentManifestRoot**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [CustomElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/customelementsymbol) &#124; null | ✘  | ✘ | ✘ | - |

_**partName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; null | ✘  | ✘ | ✘ | - |

## bindText

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | ChildNode |

**&#128966; Parameter(s)**

_**textNode**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Text | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

## declareTemplateController

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | [TemplateControllerSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/templatecontrollersymbol) |

**&#128966; Parameter(s)**

_**attrSyntax**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ | - |

_**attrInfo**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/attrinfo) | ✘  | ✘ | ✘ | - |

_**partName**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string &#124; null | ✘  | ✘ | ✘ | - |

## bindCustomAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**attrSyntax**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ | - |

_**attrInfo**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/attrinfo) | ✘  | ✘ | ✘ | - |

_**command**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | { bindingType: BindingType; compile(binding: PlainAttributeSymbol &#124; BindingSymbol): ITargetedInstruction; } &#124; null | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

## bindMultiAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**symbol**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ResourceAttributeSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |

_**attrInfo**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrInfo](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/resource-model/attrinfo) | ✘  | ✘ | ✘ | - |

_**value**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | string | ✘  | ✘ | ✘ | - |

## bindPlainAttribute

| Modifier(s)                              | Generator                          | Return Type                       |
|------------------------------------------|:----------------------------------:|-----------------------------------|
| private | ✘ | void |

**&#128966; Parameter(s)**

_**attrSyntax**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [AttrSyntax](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit/class/ast/attrsyntax) | ✘  | ✘ | ✘ | - |

_**attr**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | Attr | ✘  | ✘ | ✘ | - |

_**surrogate**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | [PlainElementSymbol](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/variable/semantic-model/plainelementsymbol) | ✘  | ✘ | ✘ | - |

_**manifest**_

| Modifier(s)                              | Type                        | Optional                           | Rest                          | Parameter Property                          | Initializer                       |
|------------------------------------------|-----------------------------|:----------------------------------:|:-----------------------------:|:-------------------------------------------:|-----------------------------------|
| - | ElementSymbol&lt;Text, HTMLTemplateElement &#124; HTMLElement, Comment&gt; | ✘  | ✘ | ✘ | - |