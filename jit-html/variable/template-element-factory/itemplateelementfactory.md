# &#128366; Summary

For some reason rollup complains about `DI.createInterface<ITemplateElementFactory>().noDefault()` with this message:
"semantic error TS2742 The inferred type of 'ITemplateElementFactory' cannot be named without a reference to '@aurelia/jit/node_modules/@aurelia/kernel'. This is likely not portable. A type annotation is necessary"
So.. investigate why that happens (or rather, why it *only* happens here and not for the other 50)

# &#128712; Attribute(s)

| Modifier(s)                            |
|----------------------------------------|
| export |

# &#128712; Variable(s)

# ITemplateElementFactory

| Type                        | Initializer                       |
|-----------------------------|-----------------------------------|
| InterfaceSymbol&lt;[ITemplateElementFactory](https://hamedfathi.gitbook.io/aurelia-2-doc-api/jit-html/interface/template-element-factory/itemplateelementfactory)&lt;INode&gt;&gt; | DI.createInterface<ITemplateElementFactory>('ITemplateElementFactory').noDefault() |